[Home](./README.md)
<div>&nbsp;&emsp;</div>

# ***Classes & Memory Management***

## why this topic matters as it relates to what iam studying in this module?

- Understanding and managing memory is directly related to my specialization in this course, as it is about writing more efficient code when you understand this topic, and it also gives you a deeper understanding of objects, properties and methods, and how much they need memory and how this is done automatically or not. When I'm done, I won't have to worry about clearing the memory.


## a) Classes, Constructors and Properties


### What’s the difference between a static and an instance constructor?

- It is simply a matter of variables or objects, since in C# it requires us to initialize data for each object created, for static constructor it is used to perform actions only once, which means that it sets up static data, and we can implement only a single static constructor for a class, and it cannot have parameters. By using the instance constructor, we set default values for fields and properties of the class and call it every time an object of the class is created, as it is allocated in memory.

### How does the use of a static constructor differ from setting properties/values?

- I may have answered an aspect of this question in my answer to the previous question. However, let me explain it in more detail here. One of the most significant features of the constructor is that there is no return type for it. As for the static constructor, it is called only once when we push the class into memory. This is unlike the instance constructor which we call every time an object is created in the class.

- static constructor like: public static int Count = 0;
- instance constructorlike: public string Name;


- public class Cat
{
    public static int Count = 0;
    public string Name;
    public int Color;



## b) Stack and Heap

### Knowing what you now know about the stack and the heap, how might you rethink the way you did projects in previous courses, to make more effecient use of memory?

Now I have a clearer understanding of the interaction of private code with memory, and how I can take advantage of that to store local variables and function call information, and this is in the memory area called the stack, and for things we need to access globally, a part of the memory called the heap. What I learned will allow me to make the most efficient use of memory. I can now distinguish between short-term memory and long-term memory. Of course, we cannot store data randomly. This will depend on the nature of the data and the period to be kept.

## c) Garbage Collection Fundamentals

### Compare “Garbage Collection” in C# with the lifecycle of normal household items.

The main difference between them is task, duration of using . While Garbage Collection is automatically managed to free up memory that the application no longer needs, and the lifecycle of normal household items is unmanaged automatically, it varies by type and usage. Also, the similarities between them are that they need management, whether it is automatic or not, so we must get rid of things that are no longer necessary.

## Things I want to know more about