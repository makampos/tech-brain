# Configuration of MediatR in .NET

MediatR is a simple, unambitious mediator implementation in .NET that helps in implementing the Command and Query Responsibility Segregation (CQRS) pattern. 

This article will guide you through the configuration process of MediatR in a .NET application.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Step 1: Install MediatR](#step-1-install-mediatr)


## Prerequisites

Before we begin, ensure you have the following:
- .NET Core SDK installed.
- A .NET Core project created.

## Step 1: Install MediatR

First, you need to install the MediatR and MediatR.Extensions.Microsoft.DependencyInjection packages. 

You can do this via the NuGet Package Manager or the .NET CLI.

Using the .NET CLI:
```
dotnet add package MediatR
dotnet add package MediatR.Extensions.Microsoft.DependencyInjection
```
