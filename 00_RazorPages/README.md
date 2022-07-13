# Razor Starter Project

### Overview

```bash
.
obj/                                    # Auto-generated files that describe the required packages
Pages/                                  # Contents of the website
    Shared/
        _Layout.cshtml                  # Layout, used by most pages
        _Layout.cshtml.css              # CSS styling for the layout
    Index.cshtml                        # The home page, written in templated C# / HTML
    Index.cshtml.cs                     # The home page's logic, written in C#
    _ViewStart.cshtml                   # Activates _Layout.cshtml
    _ViewImports.cshtml                 # Imports for .cshtml pages
    ...
Properties/                             # Settings related to the project
    launchSettings.json                 # Ports to use
wwwroot/                                # Static files, such as CSS and JS
    css/
    js/
    lib/
    favicon.ico
00_RazorPages.csproj                    # Description of the target framework (i.e. .NET 6.0)
appsettings.json                        # Connection strings and other config data
appsettings.Development.json            # Config data specific to the development environment
Program.cs                              # Entry point to the program
```

[Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/tutorials/choose-web-ui?view=aspnetcore-6.0#aspnet-core-razor-pages) are considered the simplest of the Microsoft web frameworks. Logic is largely self-contained within each page, making it easier to prototype and troubleshoot.

* Server Rendered
* Page Oriented (Not a Model-View-Controller Framework)


### Setup

1. `dotnet new webapp -o 00_RazorPages`


### Author's Notes

[Further Reading](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-6.0&tabs=visual-studio-code)

