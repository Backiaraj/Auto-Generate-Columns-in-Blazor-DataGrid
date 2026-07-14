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
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/Auto-Generate-Columns-in-Blazor-DataGrid.git
cd Auto-Generate-Columns-in-Blazor-DataGrid
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/data-annotation

**Online example**: https://blazor.syncfusion.com/demos/datagrid/data-annotation?theme=fluent