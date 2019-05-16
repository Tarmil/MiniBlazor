# Bolero - F# Tools for Blazor

[![Build status](https://ci.appveyor.com/api/projects/status/7vdtq7mkef04bbqq/branch/master?svg=true)](https://ci.appveyor.com/project/IntelliFactory/bolero)

Bolero is a set of tools and libraries to run F# applications in WebAssembly using [Blazor](https://blazor.net/).

It includes:

* **HTML** functions using a familiar syntax similar to WebSharper.UI or Elmish.React.
* **Templating** to write HTML in a separate file and bind it to F# using a type provider.
* [**Elmish**](https://elmish.github.io/elmish/) integration: run an Elmish program as a Blazor component, and Blazor components as Elmish views.
* **Routing**: associate the page's current URL with a field in the Elmish model, defined as a discriminated union. Define path parameters directly on this union.
* **Remoting**: define asynchronous functions running on the server and simply call them from the client.
* F#-specific **optimizations**: Bolero strips F# signature data from assemblies to reduce the size of the served application.

Bolero is an early stage project, and Blazor itself is considered experimental, so expect the API to fluctuate.

## Getting started with Bolero

To get started, you need the following installed:

* .NET Core SDK 2.1.403 or newer. Download it [here](https://www.microsoft.com/net/download/dotnet-core/2.1).

Then:

* Run `build.cmd`

To learn more, you can check [the documentation](https://fsbolero.io/docs).

## Contributing

Bolero welcomes contributions! If you wish to report issues, propose ideas, or submit pull requests, please use [the issue tracker](https://github.com/intellifactory/bolero). See also [the contributing guide](https://github.com/intellifactory/Bolero/blob/master/CONTRIBUTING.md) to get started on working on this repository.
