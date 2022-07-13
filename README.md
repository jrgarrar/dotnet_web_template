# ASP.Net Template

### Overview

The ASP.Net Core framework encompasses several Microsoft web frameworks. It's best suited for large-scale web projects, such as:

* Company intranets
* Web applications with complex business logic
* Web applications built around a database

***Note***: If your application doesn't require a database or user logins, consider using a lightweight tool such as [Jekyll](https://jekyllrb.com/), [Hugo](https://gohugo.io/), or [Pelican](https://blog.getpelican.com/). 

***Note***: If you prefer to use Python for your technical stack, consider [Django](https://www.djangoproject.com/).

### Setup

* Install VS Code or Visual Studio
* Install ASP.NET

### Main Technical Stack

| Tool        | Description                                                                 |
| ----------- | --------------------------------------------------------------------------- |
| C#          | An object-oriented programming language, similar to Java.                   |
| Nuget       | The package manager for C#.                                                 |
| SQL         | A programming language specialized for working with databases.              |
| Database    | An application that stores and retrieves data.                              |
| HTML/CSS/JS | The standard web development toolbox.                                       |
| EF          | The "Entity Framework", a tool that can convert C# into SQL and vice versa. |
| Razor       | A templating language that mixes HTML/CSS/JS and C#.                        |


### Helpful Tools

| Tool             | Description                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------- |
| xUnit            | A C# framework used to create repeatable tests, helpful when checking that the latest changes didn't break anything. |
| FluentValidation | A C# library that makes it easier to validate inputs, such as ensuring that a form field only takes proper dates.    |


### Advanced Usage

***Build vs. Rebuild***

Developers that use Visual Studio as their primary IDE may find themselves wondering at the difference between the **Build Solution** and **Rebuild Solution** commands.

The distinction appears to be in the thoroughness of the automated cleaning process. **Rebuild** will do a better job of removing auto-generated files, and should generally be a developer's default.

> **Note**: **Rebuild Solution** doesn't get all of the generated files either. For a more thorough clean process, copy this [.gitignore](https://github.com/dotnet/core/blob/main/.gitignore) into your project and run `git clean -xdf`.

***Adding Files to the Solution Explorer***

TBD

