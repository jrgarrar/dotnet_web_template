# Blazor Starter Project

### Overview

```bash
.
Data/
obj/                                    # Auto-generated files that describe the required packages
Pages/                                  # Contents of the website
    Index.razor
    ...
Properties/                             # Settings related to the project
    launchSettings.json                 # Ports to use
Shared/
    MainLayout.razor
    MainLayout.razor.css
    ...
wwwroot/                                # Static files, such as CSS and JS
    css/
    lib/
    favicon.ico
_imports.razor
02_Blazor.csproj                    # Description of the target framework (i.e. .NET 6.0)
appsettings.json                        # Connection strings and other config data
appsettings.Development.json            # Config data specific to the development environment
Program.cs                              # Entry point to the program
```

[Blazor]() is the newest Microsoft web framework at the time of writing. Similar to [Razor Pages](), Blazor is page-oriented rather than an MVC framework. Unlike Razor Pages, Blazor does not use JavaScript.

* Server or Client Rendered
* Page Oriented (Not a Model-View-Controller Framework)

### Setup

1. `dotnet new blazorserver -o 02_Blazor`


### Author's Notes

[Further Reading](https://docs.microsoft.com/en-us/aspnet/core/blazor/?view=aspnetcore-6.0)

