# BlazorApp

Aplicación web construida con ASP.NET Core y Blazor.

## Descripción

Este proyecto es una base para una aplicación Blazor moderna con navegación, layout y páginas de ejemplo.

## Requisitos

- .NET 10 SDK
- Visual Studio 2022 o VS Code con C# Dev Kit

## Ejecutar localmente

```bash
dotnet restore
dotnet build
dotnet run
```

Luego abre la URL indicada en la terminal, normalmente:

```text
https://localhost:5001
```

## Estructura

```text
BlazorApp/
├── Components/
│   ├── Layout/
│   ├── Pages/
│   ├── App.razor
│   ├── Routes.razor
│   └── _Imports.razor
├── Properties/
├── wwwroot/
├── Program.cs
├── appsettings.json
├── appsettings.Development.json
├── BlazorApp.csproj
└── README.md
```

## Autor

Manuel
