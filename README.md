# Project Name

Use cases of Static Modifier in Object-Oriented Programming

## Introduction
In this project, we make use of the `static` modifier using a console application based on Dotnet 6.0. 

## Static Modifier
The `static` modifier is used to declare members (fields, properties, methods) that belong to the type itself rather than to instances of the type. These members can be accessed directly using the class name, without creating an instance of the class.

The `static` modifier allows us to create shared resources and utility methods that can be accessed globally within the project. It is often used for helper functions, constants, and shared data.

To declare a `static` member, use the `static` keyword before the member declaration. For example:
```csharp
public class MyClass
{
    public static int MyStaticProperty { get; set; }

    public static void MyStaticMethod()
    {
        // Method implementation
    }
}
```
## Additional Resources
For more information and detailed examples on using the static modifier in .NET 6.0, refer to the following Medium post:

Feel free to check out the Medium post for a comprehensive guide and further insights into the static modifier.