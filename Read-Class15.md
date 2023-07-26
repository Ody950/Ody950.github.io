

# lazy loading and eager loading


## why this topic matters as it relates to what Iam studying in this module?

Using lazy loading when you have a number of entities that you do not need to access immediately is one of the best ways to improve performance in .NET development. In addition to improving performance, it can help reduce the amount of data that has to be loaded from the database. You should take advantage of eager loading in cases in which you know that you will need to access related entities immediately. By using it, fewer database queries may be executed and performance may be improved.

## Summary


## Lazy loading

In most ORM tools, such as Hibernate, SQLAlchemy, or Django ORM, lazy loading is the default behavior. Basically, the ORM will only fetch the data you explicitly request from the database, and will delay loading any related data until you make use of it. The ORM will not fetch the user's posts until you call user.posts if, for example, you have a User model and a Post model. If you need to access the related data later, this can lead to multiple queries and performance issues if you reduce the initial query time and memory usage.


## Eager loading

An eager loading approach differs from a lazy loading approach. In other words, it means that the ORM will retrieve all the information from the database that you may need in a single query, including the related data. The ORM, for example, will display the posts of the user using a subquery or a join when you query for a particular user. In this way, the performance can be improved and the N+1 query problem can be avoided, which occurs when it is necessary to make a query for every related object. In addition, eager loading can also increase query complexity and memory usage, as well as fetch unnecessary data if you do not require it.


## How I can choose


Choosing between lazy loading and eager loading depends on your application's needs and trade-offs. There is a general consensus that lazy loading is better suited to situations in which there is no frequent need to access the related data, or when you need to filter or paginate the related data. A scenario in which eager loading would be more suitable would be if you frequently access associated data, or if you need to perform calculations or aggregates on the data. Depending on the context, you can also use a hybrid approach to eagerly load some data and lazy load others.