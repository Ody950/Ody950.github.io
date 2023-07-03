


# Collections


## why this topic matters as it relates to what iam studying in this module?

Collections are used to store manage and manipulate data for example when you get data from the database like you get the list of employees okay then how you will manage that data meaning where you will store them in your application how you will do the Sorting and filtering on this data for that we need collections.
<div>&nbsp;&emsp;</div>

## Summary 

Collections are a powerful way to manage groups of objects. Unlike arrays, collections can grow and shrink dynamically as the needs of the application change. 

<div>&nbsp;&emsp;</div>

## Types of Collections

- System.Collections.Generic : Dictionary<TKey, TValue>, List<T>,Queue<T>, SortedList<TKey, TValue>, Stack<T>.
- System.Collections : ArrayList, Hashtable, Queue, Stack. 
- System.Collections.Concurrent: ConcurrentStack<T> , ConcurrentQueue<T> , ConcurrentDictionary<TKey, TValue>, BlockingCollection<T>, ConcurrentBag<T>.

<div>&nbsp;&emsp;</div>

## what is the difference between array and arraylist?

Array is storngly typed, this means that an array can store only specific type of items or elements, but arrayList can store ANY type of items or elements. Array can contain Fixed number of items, but arrayList can store ANY number of items.
<div>&nbsp;&emsp;</div>

## what is the difference between array and Hashtable?
In array we can only add items and values to the list, but in Hashtable we can add items or value with the Keys.
<div>&nbsp;&emsp;</div>

## what is the difference between List and Dictionary Collection?
List is a collection of items, Dictionary Collection of key value pair, and List is generic version of Arraylist, but Dictionary Collection is generic version of Hashtable.


Arrays are most useful for creating and working with a fixed number of strongly typed objects. Collections provide a more flexible way to work with groups of objects, collections make you  assign a key to any object you add to the collection. Collections are implemented as classes, so you must create an instance of the class before you can add elements to the collection.

<div>&nbsp;&emsp;</div>

# Enums


## why this topic matters as it relates to what iam studying in this module?

Enums are very important for any programming language, as it provides flexibility to classes that contain constants and provides storage and good access to them. This prevents errors from occurring when the program is large and facilitates writing the code through clear constants that can be used at any time.

## Summary 


An enum is a special "class" that represents a group of constants, and it is sealed class type, so it cannot be inherited. We use enums when you have values that you know will not change, to get the integer value from an item, you must explicitly convert to an int. in enum the default values are of type int if not specified, starting at 0 and increasing. 


