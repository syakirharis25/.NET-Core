# .NET-Core
My works related to .NET Core computer software framework for Windows, Linux, and macOS operating systems.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [GitHub notes.](#github)
4. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
.NET Core is a free and open-source, managed computer software framework for Windows, Linux, and macOS operating systems. It is a cross-platform successor to .NET Framework. The project is primarily developed by Microsoft and released under the MIT License.
<br /> <br />
.NET Core fully supports C# and F# (and C++/CLI as of 3.1; only enabled on Windows) and partially supports Visual Basic .NET. Currently VB.NET compiles and runs on .NET Core, but the separate Visual Basic Runtime is not implemented. Microsoft announced that .NET Core 3 would include the Visual Basic Runtime, after two years the announcement was updated to .NET Core 5.
<br /> <br />
.NET Core supports four cross-platform scenarios: ASP.NET Core web apps, command-line apps, libraries, and Universal Windows Platform apps. Prior to .NET Core 3.0, it did not implement Windows Forms or Windows Presentation Foundation (WPF) which render the standard GUI for desktop software on Windows; however, .NET Core 3 supports desktop technologies Windows Forms, WPF and Universal Windows Platform (UWP). Unlike .NET Framework, which is serviced using Windows Update, .NET Core relies on its package manager to receive updates.
<br /> <br />
Similar to how the .NET Framework implements the Common Language Infrastructure (CLI) via the Common Language Runtime (CLR) and the Framework Class Library (FCL), the two main components of .NET Core are CoreCLR and CoreFX, respectively. As a CLI implementation of Virtual Execution System (VES), CoreCLR is a complete runtime and virtual machine for managed execution of .NET programs and includes a just-in-time compiler called RyuJIT.
<br /> <br />
As a CLI implementation of the foundational Standard Libraries, CoreFX shares a subset of .NET Framework APIs, however, it also comes with its own APIs that are not part of the .NET Framework. A variant of the .NET Core library is used for UWP. The .NET Core command-line interface offers an execution entry point for operating systems and provides developer services like compilation and package management.

<a name="references"></a>
## 2. Official references websites.
Microsoft official website : https://www.microsoft.com <br />
.NET official website : https://dotnet.microsoft.com <br />
.NET official download page : https://dotnet.microsoft.com/download/dotnet-core <br />
.NET Reference Source : https://referencesource.microsoft.com <br />
.NET Developer Community : https://dotnet.microsoft.com/platform/community <br />
.NET Foundation Meetup : https://www.meetup.com/pro/dotnet/ <br />
.NET Stack Overflow : https://stackoverflow.com/questions/tagged/.net?sort=frequent <br />
.NET Architecture Guides : https://dotnet.microsoft.com/learn/dotnet/architecture-guides <br />

**_.NET Core related projects_** <br />
.NET Core Home in GitHub : https://github.com/dotnet/core <br />
.NET Source Code Integration by Mono : https://www.mono-project.com/docs/about-mono/dotnet-integration/ <br />
WinUI : https://microsoft.github.io/microsoft-ui-xaml/ <br />

**_.NET Core documentation by Microsoft_** <br />
.NET Standard : https://docs.microsoft.com/en-us/dotnet/standard/net-standard <br />
Generics in .NET https://docs.microsoft.com/en-us/dotnet/standard/generics/ <br />
Using threads and threading : https://docs.microsoft.com/en-us/dotnet/standard/threading/using-threads-and-threading <br />
.NET class library overview : https://docs.microsoft.com/en-us/dotnet/standard/class-library-overview <br />
mc:Ignorable Attribute : https://docs.microsoft.com/en-us/dotnet/framework/wpf/advanced/mc-ignorable-attribute <br />
dotnet add reference : https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-reference <br />
Microsoft.AspNetCore.Hosting Namespace : https://docs.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.hosting?view=aspnetcore-3.1 <br />
Microsoft.Extensions.DependencyInjection Namespace : https://docs.microsoft.com/en-us/dotnet/api/microsoft.extensions.dependencyinjection?view=dotnet-plat-ext-3.1 <br />
Implementing a Dispose method : https://docs.microsoft.com/en-us/dotnet/standard/garbage-collection/implementing-dispose <br />
<system.diagnostics> Element : https://docs.microsoft.com/en-us/dotnet/framework/configure-apps/file-schema/trace-debug/system-diagnostics-element <br />

**_.NET Core related documentation by Microsoft_** <br />
WinUI 3.0 Alpha (February 2020) : https://docs.microsoft.com/en-us/uwp/toolkits/winui3/ <br />

**_.NET Core questions and answers by Stack Overflow_** <br />
Use WPF with .NET Standard Library by Stack Overflow : https://stackoverflow.com/questions/57529594/use-wpf-with-net-standard-library <br />
What is really a Principal in .NET? by Stack Overflow : https://stackoverflow.com/questions/28436332/what-is-really-a-principal-in-net <br />

**_.NET related articles_** <br />
What’s The Difference Between .NET Core Vs .NET Framework by Amar InfoTech : https://www.amarinfotech.com/difference-between-net-core-2-0-vs-net-framework.html <br />
dotnet build failed #8071 by GitHub : https://github.com/dotnet/runtime/issues/8071 <br />
 
<a name="github"></a>
## 3. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/.NET-Core.git
$ cd .NET-Core/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 4. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
JSON                            57              0              0          27728
JavaScript                      13           4376           4090          16570
CSS                              7           1466             49          12666
C#                              50            170            231           1335
Razor                           10              8              0            146
Markdown                         2             15              0             79
MSBuild script                   7             17              0             54
XML                              5              0              0             49
XAML                             2              2              0             19
-------------------------------------------------------------------------------
SUM:                           153           6054           4370          58646
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
