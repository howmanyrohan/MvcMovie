# MVC Movie Web App Tutorial

This tutorial provides step-by-step instructions on creating an MVC (Model-View-Controller) web application for managing movie data using ASP.NET Core. It covers the fundamental concepts and key features of ASP.NET Core MVC, guiding you through the process of building a functional movie listing application.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed on your development machine:

- [.NET SDK](https://dotnet.microsoft.com/download) (version specified in the tutorial)
- [Visual Studio](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/download) (with C# extension) or any other preferred text editor

## Getting Started

1. Clone the repository or download the project files from the tutorial page.

   ```
   git clone https://github.com/howmanyrohan/MvcMovie.git
   ```

2. Open the project in Visual Studio.

     - Click on "Open a project or solution."
     - Navigate to the project directory and select the solution file (.sln).


3. Build the solution.

   ```
   Ctrl + Shift + B
   ```
4. Install required NuGet Packages.
Go to '''Tools > Nuget Package Manager > Manage Nuget Packages for Solution .. '''
    **Install**
      - Microsoft.EntityFrameworkCore.SqlServer
      - Microsoft.EntityFrameworkCore.Tools
      - Microsoft.VisualStudio.Web.CodeGeneration.Design
    
 5. Initialize local database.

   ```
   Update-Database
   ```

6. Run the application without debug.

   ```
   Ctrl + F5
   ```


## Tutorial Contents

The tutorial consists of multiple steps, each focusing on a specific topic. Here's an overview of the tutorial contents:

1. Step 1: **Create a New ASP.NET Core MVC Project**
   - Creating a new ASP.NET Core MVC project using the dotnet CLI or Visual Studio template.

2. Step 2: **Add a Model**
   - Creating a movie model to represent the movie data.

3. Step 3: **Scaffold the Movie Controller and Views**
   - Generating the controller and views using the dotnet CLI or Visual Studio scaffolding tools.

4. Step 4: **Working with a Database**
   - Setting up a local database MS SQL Server Express LocalDB.
   - Migrating the database schema using Entity Framework Core.
   
5. Step 4: **Add Search and New Field**
   - - Adding Search and genre filtering functionality to the movie list.

6. Step 5: **Add Validation**
   - Implementing data validation on the movie model.

7. Step 6: **Add Detail Examination and Delete Functionality**
   - Adding Detail and Delete functionality to the movie list.


## Reference

-[ASP.NET Core MVC Tutorial](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app)


## Conclusion

By following this tutorial, I gained a solid understanding of ASP.NET Core MVC and be able to build your own movie listing application using the MVC architectural pattern.
