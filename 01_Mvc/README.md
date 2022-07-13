# MVC Starter Project

### Overview

```
.
.vscode/                                # Configurations for the VS Code editor, including launch/debug commands
    launch.json
    tasks.json
bin/                                    # Auto-generated files for various purposes
Controllers/                            # C# files that fetch data, update data, route requests, etc.
    HomeController.cs
Models/                                 # Database objects represented with C#
    ErrorViewModel.cs 
obj/                                    # Auto-generated files that describe the required packages
Properties/                             # Settings related to the project
    launchSettings.json                 # Ports to use
Views/                                  # .cshtml files, mixing C# and HTML
    Home/
        Index.cshtml                    # Home page
        Privacy.cshtml
    Shared/
        _Layout.cshtml                  # Template layout for various pages
    _ViewImports.cshtml                 # Imports for .cshtml pages
    _ViewStart.cshtml
wwwroot/                                # Static files, such as CSS and JS
    css/
    js/
    lib/
    favicon.ico
appsettings.json                        # Connection strings and other config data
appsettings.Development.json            # Config data specific to the development environment
MvcMovie.csproj                         # Description of the target framework (i.e. .NET 6.0)
Program.cs                              # Entry point to the program
```

[ASP.Net Core MVC](https://docs.microsoft.com/en-us/aspnet/core/tutorials/choose-web-ui?view=aspnetcore-6.0#aspnet-core-mvc) is a web framework for implementing the Model-View-Controller pattern. Unlike the Razor Pages framework, logic is separated between three components (Models, Views, Controllers). This has the benefit of making the User Interface components more resistant to database changes. However, it comes at the cost of significantly higher complexity for the project.

* Server Rendered
* Model-View-Controller Framework


### Setup

1. `$dotnet new mvc -o 01_Mvc`


### Author's Notes

[Further Reading](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-6.0&tabs=visual-studio)

Even with the current iteration of .NET 6.0, these projects can be difficult to work with. The structure and file organization are considerably less straightforward than other technical stacks I've seen, with the possible exception of a few Java frameworks. Likewise, the process to get a simple project off the ground involves a hefty amount of work.

Developers who are familiar with this tech stack seem to implement their own tooling to get around these shortcomings. `gulp`, for example, can simplify the running and testing of an MVC project by organizing those processes within a JavaScript wrapper. 

