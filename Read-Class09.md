
# LINQ


## why this topic matters as it relates to what Iam studying in this module?

It allows the querying of any type of data source using a common syntax and language features in C#. Using it, we were able to access data from various sources, including objects, data sets, SQL Server, and XML. And give us a solution for the problem of object-relational mapping and simplifies the interaction between objects and data sources.

## Summary

The LINQ acronym stands for Language Integrated Query. This is a set of technologies that integrate query capabilities directly into C#. A query is a first-class construct in LINQ, just like classes, methods, and events. It is possible to write queries against strongly typed collections of objects by using language keywords and familiar operators. For each of the three LINQ technologies (LINQ to Objects, LINQ to SQL, and LINQ to XML), a consistent query experience is provided. You can write LINQ queries in C# for SQL Server databases, XML documents, ADO.NET Datasets, and any collection of objects that supports IEnumerable or the generic IEnumerable interface.


## There are three parts to a query operation

- Obtain the data source.

- Create the query.

- Execute the query.




## LINQ queries in C# we have two ways to write the code:

- Query Syntax
```
  var List = from item in books orderby item.Id descending select item;
```
- Non-Query Syntax
```
  var List = books.OrderBy(item => item.Id);
```


## Basic LINQ Query Operations


- Obtaining a Data Source

The range variable functions similarly to the iteration variable in a foreach loop except that no actual iterations are performed during the execution of the query. 
```
var queryAllCustomers = from cust in customers select cust;
```
- Filtering

Using the filter, the query returns only those elements that satisfy the expression. By using the where clause, we are able to produce the result. 
```
var queryLondonCustomers = from cust in customers where cust.City == "London" select cust;
```

- Ordering

Ordered by the default comparator for the type being sorted, the elements in the returned sequence will be sorted accordingly. Using the following query, we can sort the results based on  item Id.
```
  var List = from item in books orderby item.Id descending select item;
```

- Grouping

By using the group clause, you are able to group your results according to a specified key.
```
var queryCustomersByCity = from cust in customers group cust by cust.City;
```
- Joining

There is no explicit modeling of the data sources with the insertion of join operations, thereby resulting in associations between sequences that are not explicitly modeled. 
```
var innerJoinQuery = from cust in customers join dist in distributors on cust.City equals dist.City select new { CustomerName = cust.Name, DistributorName = dist.Name };
```
