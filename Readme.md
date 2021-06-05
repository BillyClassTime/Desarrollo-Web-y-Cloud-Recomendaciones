# Instalaciones y configuraciones

1. Install Microsoft Visual Studio 2019 Community Edition 
   1. [Download Visual Studio 2019 for Windows & Mac (microsoft.com)](https://visualstudio.microsoft.com/downloads/)
2. Install Microsoft SQL Server 2019 Express Edition 
   1. [Download Microsoft® SQL Server® 2019 Express from Official Microsoft Download Center](https://www.microsoft.com/en-us/Download/details.aspx?id=101064)
3. Install .Net SDK 5.0, 3.1 y 2.1 (Windows 10 Professional Edition recommended)
   1. [Download .NET (Linux, macOS, and Windows) (microsoft.com)](https://dotnet.microsoft.com/download)
      1. [Download .NET 5.0 SDK (v5.0.300) - Windows x64 Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.300-windows-x64-installer)
      2. [Download ASP.NET Core 5.0 Runtime (v5.0.6) - Windows Hosting Bundle Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-5.0.6-windows-hosting-bundle-installer)
      3. [Download .NET Core 3.1 SDK (v3.1.409) - Windows x64 Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-3.1.409-windows-x64-installer)
      4. [Download ASP.NET Core 3.1 Runtime (v3.1.15) - Windows Hosting Bundle Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-3.1.15-windows-hosting-bundle-installer)
      5. [Download ASP.NET Core 2.1 Runtime (v2.1.28) - Windows Hosting Bundle Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-aspnetcore-2.1.28-windows-hosting-bundle-installer)
      6. [Download .NET Core 2.1 SDK (v2.1.816) - Windows x64 Installer (microsoft.com)](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-2.1.816-windows-x64-installer)
4. Install Visual Studio Code 
   1. [Download Visual Studio Code - Mac, Linux, Windows](https://code.visualstudio.com/Download)
5. Sign up for Docker Hub 
   1. [Docker Hub](https://hub.docker.com/)
6. Install Azure CLI 
   1. https://aka.ms/installazurecliwindows
7. Install node.js 
   1. [Node.js (nodejs.org)](https://nodejs.org/en/)
8. Install git 
   1. [Git - Downloading Package (git-scm.com)](https://git-scm.com/download/win)
9. Install Command Line Tools for Azure Functions 
   1. ``` npm i -g azure-functions-core-tools@core --unsafe-perm tru ```
10. Install DB Browser for SQLite 
    1. [DB Browser for SQLite (sqlitebrowser.org)](https://sqlitebrowser.org/)
11. Activate Internet Information Services(IIS) Manager 
    1. Open Control Panel, Select Programs, and then click Turn Windows  features on or off.
    2. Click Yes on User Account Control dialog box.
    3. Select Internet Information services checkbox and click OK.
    4. On Windows Features page, click close.
12. Install SQL Operations Studio (Azure Data Studio)
    1. https://go.microsoft.com/fwlink/?linkid=2163435

13. Install HttpRepl
    1. ``` dotnet tool install -g Microsoft.dotnet-httprepl ```

14. Install Azure Power Shell 
    1. ``` Install-Module -Name Az -Scope CurrentUser -Repository PSGallery -Force ```
    2. [Install Azure PowerShell with an MSI | Microsoft Docs](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps-msi?view=azps-6.0.0) **(Alternativa al punto anterior, si se elije este no se hace el anterior y viceversa)**

15. Install Windows Terminal
    1. [Get Windows Terminal - Microsoft Store](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701#activetab=pivot:overviewtab)

16. Azure Storage Emulator
    1. https://go.microsoft.com/fwlink/?linkid=717179&clcid=0x409
17. Cosmos DB Emulator
    1. https://aka.ms/cosmosdb-emulator
18. Install Visual Studio Code Extensions (Desde Visual Studio Code)
    1. [Prettier - Code formatter - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    2. [Azure Tools - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-node-azure-pack)
    3. [XML Tools - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
    4. [C# - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
    5. [Git History - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
    6. [GitLens — Git supercharged - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    7. [Markdown Editor - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=zaaack.markdown-editor)
    8. [PowerShell - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)



# 20480C - HTML, JavaScript, CSS3

Del curso 20480 deberéis realizar cuando podais los siguientes laboratorios

| Module | Description                | Lab                                                          |
| ------ | -------------------------- | ------------------------------------------------------------ |
| Mod 1  | Overview of HTML and  CSS  | Exploring the  Contoso Conference Application<br />Examining and Modifying the Contoso Conference Application |
| Mod 3  | Introduction to JavaScript | Displaying Data and Handling Events by Using JavaScript.<br />Displaying Data Programmatically<br />Handling Events |

# 20483C - C#

Estos son los capitulos a leer y revisar de este curso. No es necesario hacer los laboratorios, pues estan orientados a desarrollos windows form con XAML y es una tecnología en desuso. Aquí es importante el concepto del lenguaje y demás temas que os encontraréis en los primeros 6 módulos.

| Course 20483-C:  Programming in C#                           |
| ------------------------------------------------------------ |
| Module 1: Review of Visual C# Syntax                         |
| Module 2: Creating Methods, Handling  Exceptions, and Monitoring Applications |
| Module 3: Basic types and constructs of  Visual C#           |
| Module 4: Creating Classes and  Implementing Type-Safe Collections |
| Module 5: Creating a Class Hierarchy by  Using Inheritance   |
| Module 6: Reading and Writing Local Data                     |

Para complementar el aprendizaje de C# los Microsoft Learning Path asi:

| Module                                                       | Description and URL                                          |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Take  your first steps with C#                               | https://docs.microsoft.com/en-us/learn/paths/csharp-first-steps/     Take your first steps with C# - Learn     Interested in learning a programming language but aren't sure where to  start? Start here! Learn the basic syntax and thought processes required to  build simple applications using C#.     docs.microsoft.com |
| Add  logic to your applications with C#                      | https://docs.microsoft.com/en-us/learn/paths/csharp-logic/     Add logic to your applications with C# - Learn     Deepen your experience with C# logic and iteration statements, Boolean  expressions, and code blocks in this Learning Path.     docs.microsoft.com |
| Work with  data in C#                                        | https://docs.microsoft.com/en-us/learn/paths/csharp-data/     Work with data in C# - Learn     Dive deeper into data and types, learning how to manipulate string and  numeric data.     docs.microsoft.com |
| Build  .NET applications with C#                             | https://docs.microsoft.com/en-us/learn/paths/build-dotnet-applications-csharp/     Build .NET applications with C# - Learn     .NET is a free, cross-platform, open source developer platform for building  many different types of applications. With .NET, you can use multiple  languages, editors, and libraries to build for web,...     docs.microsoft.com |
| Interactively debug .NET apps with the Visual Studio  Code debugger | https://docs.microsoft.com/en-us/learn/modules/dotnet-debug/     Interactively debug .NET apps with the Visual Studio Code debugger -  Learn     Learn how to efficiently debug your .NET app by using Visual Studio Code to  fix your bugs quickly. Use the interactive debugger within Visual Studio Code  to analyze and fix your C# applications.     docs.microsoft.com |

# 20486D - ASP.Net Core MVC

| Module | Description | Lab  |
| ------ | ----------- | ---- |
| Mod 1 | Exploring ASP.NET Core MVC | Exploring ASP.NET  Core MVC<br />Exploring a Razor Pages Application<br />Exploring a Web API Application<br />Exploring an MVC Application |
| Mod 3 | Configure Middlewares and  Services in ASP.NET Core | Configuring  Middleware and Services in ASP.NET Core<br />Working with Static Files<br />Creating custom middleware<br />Using dependency injection<br />Injecting a service to a controller |
| Mod 4 | Developing Controllers                              | Developing  Controllers<br />Adding controllers and actions to an MVC application<br />Configuring routes by using the routing table<br />Configuring routes using attributes<br />Adding an action filer |
| Mod 5 | Developing Views                                    | Developing  Views<br />Adding Views to an MVC Application<br />Adding a partial view<br />Adding a view component |
| Mod 6 | Developing Models                                   | Developing  Models<br />Adding a model<br />Working with Forms<br />Add Validation |

# 20487D - Developing Microsoft Azure and Web Services

| Module | Descripción del módulo                                       | Laboratorio                                                  |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Mod 1  | Descripción general del servicio y las tecnologías en la nube | Exploración del ambiente de trabajo    <br />Crear un proyecto ASP.NET Core     <br />Crear un modelo simple de Entity Framework     <br />Crear una clase de API web     <br />Implementar la aplicación web en Azure |
| Mod 2  | Consultar y manipular datos con Entity Framework             | Crear una capa de  acceso a datos utilizando Entity Framework<br />Crear un modelo de datos     <br />Consultar la base de datos |
| Mod 2  | Consultar y manipular datos con Entity Framework             | Manipular  datos     <br />Crear métodos de repositorio     <br />Probar el modelo usando SQL Server y SQLite |
| Mod 3  | Creación y consumo de API web ASP.NET Core                   | Crear una API web  básica de ASP.NET<br />Crear una clase de controlador     <br />Usar la API desde un navegador     <br />Crear un cliente |
| Mod 4  | Ampliación de los servicios HTTP ASP.NET Core                | Customizing the  ASP.NET Core Pipeline <br />Use Dependency Injection to Get a Repository Object<br />Create a Cache Filter<br />Create a Debugging Middleware |

