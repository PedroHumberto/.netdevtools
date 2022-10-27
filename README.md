# Intro
**Alan Freeman** - Pro ASP.NET Core 3 Develop Cloud-Ready Web Applications Using MVC, Blazor, and Razor Pages

*This content has some quotes from from this book.*

---

# Using the Dev Tools

Learning how to use de dev tools (Managing Packages)

Links:

* [Nuget](nuget.org)
* [Libman](https://cdnjs.com)
* [Bootstrap](https://getbootstrap.com/)

---
# Learning about Packages

## Managing Packages:
[dotnet list package]

dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 3.1.1
* Installs version 3.1.1 oof the Microsoft.EntityFrameworkCore.SqlServer package

---

## Tool Packages
Install an Entity Framework Core tools
First you need to verify if dotnet-ef is installed (``dotnet tool uninstall --global dotnet-ef``)

``dotnet tool install --global dotnet-ef --version 3.1.1``

---

## Client-Side Packages
Client-side packages contain content that is delivered to the client, such as images, CSS stylesheets, JavaScript files, and static
HTML.
In your pc global installing:
``dotnet tool uninstall --global Microsoft.Web.LibraryManager.Cli``


``dotnet tool install --global Microsoft.Web.LibraryManager.Cli --version 2.0.96``

Initializing the libman
``libman init -p cdnjs``

Now we can download Bootstrap CSS
``libman install twitter-bootstrap@5.2.2 -d wwwroot/lib/twitter-bootstrap``
