
# Hash Tables

## why this topic matters as it relates to what Iam studying in this module?

In .NET, we can use something called the Dictionary<TKey, TValue> class, which works like a special storage box known as a hash table. This helps us quickly put things in and take things out, like keys and their associated values. This is super important for us as developers, especially when we're dealing with tasks like storing stuff temporarily, making lists that are easy to search, or managing groups of things where we don't want duplicates.

We also have another tool in our .NET toolbox called HashSet<T>, which is another type of storage box based on this hash stuff. With this, we can easily make sure we don't have the same thing twice in our list of items. This keeps our data neat and tidy and helps us save computer memory too.


## Summary


A hash table is a data structure that stores data in an organized way using unique index values in an array format. This allows for fast data access if you know the specific index of the data you're looking for. In essence, it's a data structure where adding and finding data is quick, regardless of how much data you have. Hash tables use arrays for storage and employ a hashing technique to determine where to insert or find elements.

### Structure

Hashing is a process of converting data into a fixed-length string of letters and numbers using a special algorithm called a hash function. The input data to be hashed is also known as the key. The central part of any hashing process is the hashing function, which takes the key and converts it to a fixed-length string of characters. A hash code turns a key into an integer, and it’s important that hash codes are deterministic: their output is determined only by their input. Hash codes should never have randomness to them, and the same key should always produce the same hash code.

A hashtable traditionally is created from an array. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value. Here is a possible suggestion:

Add or multiply all the ASCII values together.
Multiply it by a prime number such as 599.
Use modulo to get the remainder of the result when divided by the total size of the array.
Insert into the array at that index.


### Hash function

A hash function is a mathematical function that maps data of arbitrary size to fixed-size values, called hash values, hash codes, digests, or simply hashes. The hash function is a central part of any hashing process, and it’s important to have a good hash function that meets the following basic requirements:

- Easy to compute: It should be easy to compute and must not become an algorithm in itself.
- Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.
- Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.

