# BlazorApp

Aplicación web desarrollada con ASP.NET Core y Blazor, pensada como base para proyectos modernos con interfaz interactiva y arquitectura de componentes.

## Descripción

Este proyecto incluye una estructura básica de una aplicación Blazor con:

- Layout principal
- Menú de navegación
- Páginas de ejemplo (`Home`, `Counter`, `Weather`)
- Configuración estándar de ASP.NET Core
- Estilos y assets iniciales

Es una excelente base para empezar a construir una aplicación web más compleja.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- .NET SDK 10
- Visual Studio 2022 o VS Code con la extensión C#
- Git

## Instalación

```bash
git clone https://github.com/manuelpaz/BlazorApp.git
cd BlazorApp
 dotnet restore
```

## Ejecutar localmente

```bash
dotnet build
dotnet run
```

Luego abre la URL que indique la terminal. En un entorno local normalmente será algo como:

```text
https://localhost:5001
```

## Estructura del proyecto

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
├── README.md
├── LICENSE
└── .gitignore
```

## Funcionalidades base

- Navegación entre páginas en Blazor
- Componentes reutilizables
- Soporte para Bootstrap por defecto
- Configuración lista para desarrollo y despliegue

## Uso

Puedes usar este proyecto como punto de partida para:

- dashboards,
- CRUDs,
- paneles administrativos,
- portales internos,
- aplicaciones empresariales web.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Autor

Manuel
