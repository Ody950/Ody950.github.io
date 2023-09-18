

# View Components




## why this topic matters as it relates to what Iam studying in this module?

We can use view components in .NET to separate HTML from logic code, making our code more maintainable and testable. It is possible to reuse View components across different views, reducing code duplication and improving the efficiency of development. We can easily inject dependencies in our code using the View and the constructor components, allowing us to write testable, clean codes.

## Summary

An important aspect of View Components is that they are powerful, self-contained, and reusable UI components that can consistently be used to generate reusable HTML from a razor view. In addition to generating static content, they are also capable of generating dynamic content that can be further customized by adjusting parameters. You may also use View Components to retrieve data from backend databases or services.


## A view component:

- Renders a chunk rather than a whole response.
- Includes the same separation-of-concerns and testability benefits found between a controller and view.
- Can have parameters and business logic.
- Is typically invoked from a layout page.




## View Components: Important points to remember

- The View Components provide separation of concerns and testability benefits since they produce consistent output wherever they are utilized.

- This type of component is suitable for rendering chunks rather than a complete response. In this regard, they are ideal for rendering user interface elements, widgets, dynamic menus, shopping carts, login pages, sidebars, and so on.  

- You can parameterize view components in order to customize the output, and they may also have their own business logic.

- There are no features such as View Data or Data Binding that are available in View Components and they rely solely on the parameters that are provided to them at runtime  




## The following steps can be taken to create a view component:

- You will need to create a class derived from ViewComponent.

- Add the attribute [ViewComponent] to a class.

- Add the suffix ViewComponent to the name of the class.

- You may choose any one of these options or even combine them.


