# Auto Generate Columns in Blazor DataGrid

A sample Blazor application demonstrating how to leverage **data annotations** to automatically generate and customize columns in the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This repository shows how to use `System.ComponentModel.DataAnnotations` to automatically generate DataGrid columns from your data model. By applying attributes like `[Display]`, `[ReadOnly]`, and `[DisplayFormat]`, you can control column headers, order, formatting, and visibility without writing manual column definitions in your Razor components.

## Features

- **Data Annotation Support** - Use `[Display]`, `[ReadOnly]`, and `[DisplayFormat]` for declarative configuration
- **Column Customization** - Control column headers, order, visibility, and formatting without code repetition
- **Inline Editing** - Edit, update, and delete records with built-in edit toolbar support
- **Read-only Fields** - Mark specific properties as read-only to prevent user modifications
- **Data Formatting** - Apply custom formatting to numeric, date, and other data types
- **CRUD Operations** - Complete example demonstrating create, read, update, and delete operations

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`DataAnnotationSample.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd Auto-Generate-Columns-in-Blazor-DataGrid
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Documentation**: https://help.syncfusion.com/grid-sdk/blazor/data-grid/data-annotation

**Online example**: https://blazor.syncfusion.com/demos/datagrid/data-annotation?theme=fluent2