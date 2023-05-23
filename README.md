<p align="center">
  <img src="IndieDuck.jpg" alt="Logo" width="150" height="150">
</p>

<h2 align="center">Welcome to IndieDuck Studio!</h2>

<p align="center"> <i><strong>Quack-tastic Creations Unleashed: Embrace the Indie Spirit with Indie Duck Studio!</strong></i> </p>
 
<p align="center">
        IndieDuck Studio - is a dynamic and creative game development team<br>
        that is passionate about creating unique and captivating gaming experiences.<br>
        With a focus on indie game development, our talented team of developers,<br>
        designers, and artists work collaboratively to craft innovative and memorable games<br>
        that push the boundaries of creativity and gameplay.<br>
        From quirky and charming adventures to fast-paced action games,<br>
        IndieDuck Studio is committed to delivering high-quality games<br>
        that captivate players and leave a lasting impression.<br>
        Join us on our journey as we create exciting games<br>
        that bring joy to players around the world!<br>
</p>

# Project Documentation
## Overview
In this introduction Wiki you are gonna learn everything you need to know to get started.<br>

> IDE - **Optional**<br>
> Framework - **Unity Engine**<br>
> API's - **Unity API**<br>
> Conventions and Principles - [Microsoft C# Documentation](https://learn.microsoft.com/en-us/dotnet/csharp/)<br>

## Coding Conventions

### Naming Conventions
* > Constants: Use PascalCase.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/1f931265-1867-4bd6-9015-ed241b931761)

* > Classes and Structs: Use PascalCase.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/49e18192-1608-4de8-bd53-be43f12a0e93)

* > Methods and Functions: Use PascalCase.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/31802817-c7e6-4f9e-906e-3de070ede62e)  
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/ace845a9-3ccd-4a60-9f9f-bdcc68fd03ef)

* > Variables and Parameters: Use camelCase.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/19ffbbc6-2f3e-4990-b6a5-657a5d3ee7fb)  
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/44060d7d-8593-4104-91d6-9b081f750966)

* > Enums: Use PascalCase for enum types and PascalCase or ALL_CAPS for enum values, depending on the situation.<br>
_Enum Type (Enum Name) - PascalCase:<br>_
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/c19afb4e-1831-4837-b5cf-9b7d47f64ffc)  
_Enum Values (Enum Members) - PascalCase (Regular Values):<br>_
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/e5e2b475-eea9-4421-bf5d-0277472b9635)  
_Enum Values (Enum Members) - ALL_CAPS (Special Constants or Flags):<br>_
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/bc152df0-eae0-4d71-b3bd-47ddc4c1854f)  
**NOTE: The choice between PascalCase and ALL_CAPS for enum values depends on their significance and usage within your specific scenario.**

### Code Formatting
* > Indentation: Use spaces for indentation with a consistent number of spaces (4 spaces).<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/0e106137-be06-4214-982f-41e919c69d2d)<br>

* > Braces: Place opening braces on the same line as the corresponding statement or declaration. Use a new line for closing braces.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/d99da44b-aa25-4059-9eee-4ccbe970d873)<br>

* > Line Length: Limit lines to a maximum of 120 characters.

* > Comments: Use XML comments for public members, and single-line or multi-line comments for code explanations and clarifications.

### Documentation Comments
* > Use XML documentation comments to provide descriptive and meaningful documentation for classes, methods, properties, and parameters.<br>
_comment is placed immediately above the method declaration and provides documentation for the Add method._<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/a05f20b6-1044-4692-ac28-d9d2506a4205)  

* > Include information about the purpose, usage, and expected behavior of each member.<br>
_Providing the explanation to each member of a method. PS: Use it when it's not that obvious 
( comments below is just an example of how it should be done with anything else )_<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/94d4974e-4efc-498e-bfcd-49338848f0bb)  
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/8b38595d-85ce-4ab7-8817-8dcd72066fc6)  

* > Document any exceptions that can be thrown and any specific considerations for using the member.<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/3d512f5a-c1ee-4738-b7bf-c80b3b967a81)  

**NOTE: When you write XML comments in your code, they can be extracted to generate API documentation
that can be consumed by developers who use your code. 
This documentation helps them understand how to use your methods,
what parameters they should provide, and what they can expect in return.**

### Design Patterns
Document the design patterns utilized in the project, along with their purpose and usage. Include examples where appropriate. Some common design patterns used in C# projects are:<br>

* > Singleton Pattern<br>
* > Factory Pattern<br>
* > Builder Pattern<br>
* > Observer Pattern<br>
* > Strategy Pattern<br>
* > Decorator Pattern<br>

### Design Principles
Follow the design principles to ensure that the codebase is easy to modify, change, add, remove, and read in the future.<br>
The design principles provide guidelines for creating well-structured and maintainable code.<br>
Here are some key design principles to consider:<br>

* > Keep the codebase clean and well-organized: Maintain a clean and organized codebase by following consistent naming conventions, proper indentation, and logical file and folder structures.<br>

* > Follow the SOLID principles: The SOLID principles are a set of guidelines that help in designing maintainable and flexible software. They include:<br>

* > Apply the DRY (Don't Repeat Yourself) principle: Avoid duplicating code or logic. Encourage modularization and reuse of common functionality to improve maintainability and reduce code duplication.<br>

* > Write clear and concise code: Use meaningful variable and function names that accurately describe their purpose and behavior. Write code that is easy to understand and read by other developers.<br>

* > Utilize object-oriented programming concepts: Apply object-oriented programming principles such as encapsulation, inheritance, and polymorphism to create modular and reusable code. Design classes and relationships that reflect real-world entities and their interactions.<br>

### SOLID Principles
* > Single Responsibility Principle (SRP): Each class or module should have only one reason to change.<br>
* > Open-Closed Principle (OCP): Software entities should be open for extension but closed for modification.<br>
* > Liskov Substitution Principle (LSP): Subtypes must be substitutable for their base types.<br>
* > Interface Segregation Principle (ISP): Clients should not be forced to depend on interfaces they do not use.<br>
* > Dependency Inversion Principle (DIP): High-level modules should not depend on low-level modules. Both should depend on abstractions.<br>

### DRY (Don't Repeat Yourself) Principle
Avoid duplicating code or logic. Encourage modularization and reuse of common functionality.<br>

### KISS (Keep It Simple, Stupid) Principle
Strive for simplicity and readability in code and design. Avoid unnecessary complexity.

### File and Folder Structure
Project folder starting from Assets/ has 3 levels of folders.<br>
A/B/C - Every level contains stuffs related to particular topic:<br>
![image](https://github.com/IndieDuck-Studio/Getting-Started/assets/115007251/268785b4-10d4-43c0-a36f-7586a4a1f33a)<br>
* > A-Miscellaneous/: Contains ProjectPackages & Plugins & Development folders ( used for technical purposes ).<br>
* > B-Rendering/: Contains everything related to Graphics & Rendering & Textures.<br>
* > C-Game/: Contains core files of game itself, Scripts, Animations etc.<br>

### Dependencies and Third-Party Libraries
* > UniversalRenderPipeline2D - Package for immitating Lights and Shadows.
* > New Unity InputSystem - Package for comfortable and flexible control of Inputs.


### Build and Deployment
TODO: Document the build and deployment process for the project. Include steps, configurations, and any required tools or scripts.<br>

### Testing and Quality Assurance
TODO: Explain the testing approach followed by the team, including unit testing, integration testing, and any additional quality assurance measures.<br>

### Maintenance and Support
TODO: Provide guidelines for maintaining the project, handling bug reports, and addressing support requests.<br>

### Version Control
Explain the Git workflow used by the team, including branch naming conventions, commit message guidelines, and repository management.<br>

### Conclusion
In conclusion, IndieDuck Studio is a dynamic and creative game development team passionate about creating unique and captivating gaming experiences. They utilize the Unity Engine and Unity API for their projects and follow the coding conventions and design principles outlined in the Microsoft C# Documentation.<br>

The documentation provides comprehensive guidelines for naming conventions, code formatting, documentation comments, design patterns, and SOLID principles. These guidelines ensure that the codebase is well-organized, maintainable, and follows industry best practices.<br>

By adhering to these conventions and principles, IndieDuck Studio aims to create clean, modular, and reusable code that is easy to understand and modify. They emphasize the importance of writing clear and concise code with meaningful names, utilizing object-oriented programming concepts, and avoiding code duplication.<br>

Additionally, the documentation covers important aspects such as file and folder structure, dependencies and third-party libraries, build and deployment processes, testing and quality assurance, maintenance and support guidelines, and version control practices.<br>

By following these guidelines and principles, IndieDuck Studio strives to deliver high-quality games that push the boundaries of creativity and gameplay. They invite players from around the world to join them on their exciting journey and experience the joy and excitement of their meticulously crafted games.<br>

IndieDuck Studio embodies the indie spirit, embracing innovation and creativity in their game development endeavors. Their dedication to following industry standards and best practices ensures that their games captivate players and leave a lasting impression.<br>

Welcome to IndieDuck Studio, where quack-tastic creations are unleashed, and the indie spirit thrives!<br>
