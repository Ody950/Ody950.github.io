

# MVC Forms


# View Model

## why this topic matters as it relates to what Iam studying in this module?
We use views as developers to ensure separation of concerns by separating the user interface markup from other parts of the application. In this way, the app becomes modular and easier to maintain as a result of its better organization. There is usually a grouping of views by the features of the app, which makes it easier to locate related views when working on a feature. Considering that the parts of the application are loosely coupled, it is possible to construct and update the views of the application separately from its data access and business logic.

## Summary
Model View Controller patterns typically involve the View, which is responsible for displaying the model data (the model data provided by a controller) as a UI with which the end user can interact. Every action method of a controller can return a different view. The controller has the capability of rendering one or more views. As a result, the MVC framework assumes that each controller will have a separate subfolder within the Views folder that will have the same name as the controller. Views are responsible for presenting application data in ASP.NET Core MVC applications. This means that we are only using the views to display information about the website in the browser. In general, the user executes all of the actions on a view, such as clicking a button, completing a form, adding items to a list, and so forth.In addition, it is responsible for presenting content through the user interface.

### Creating a view
To create a view, add a new file and give it the same name as its associated controller action with the .cshtml file extension. To create a view that corresponds with the About action in the Home controller, create an About.cshtml file in the Views/Home folder.


### Pass data to views
Pass data to views using several approaches, Strongly typed data: viewmodel, Weakly typed data ViewData (ViewDataAttribute) ViewBag.


# Form In ASP.NET MVC

## why this topic matters as it relates to what Iam studying in this module?
As .NET programmers, forms are crucial to our work because they enable us to collect data from the user and forward it to the server for processing. In addition, it facilitates the creation of interactive and responsive web applications. It is through forms that our application can be interacted with by users.

## Summary
### How to create Forms in ASP.NET MVC?

1- Weakly Typed (Synchronous) Advantage and Disadvantage of Weakly Typed Form

### Advantage:

- It is easy to create a form using Weakly Typed mechanism
- Mostly used when you need to create a form with one or two input items.

### Disadvantage:

- Because, it is not strongly typed so IntelliSense doesn't help you.
- Have higher chance of getting exception and runtime error messages.
- Very difficult to manage when forms have multiple input items and controls.
- It is very clumsy when you need to add or remove some input items.
2- Strongly Typed (Synchronous)
3- Strongly Typed AJAX (Asynchronous)
4- HTML, AJAX and JQUERY



