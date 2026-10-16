# Customize the Edit Dialog Using Templates in Blazor TreeGrid

## Overview

This sample demonstrates how to customize dialog editing in the Syncfusion [Blazor TreeGrid](https://www.syncfusion.com/blazor-components/blazor-tree-grid) component using edit templates. Instead of relying on the default edit dialog layout, the implementation provides a customized dialog interface that allows developers to control the editors, layout, and user experience presented during add and edit operations. This approach is useful when additional validation, custom input controls, or business-specific editing workflows are required for hierarchical data maintained through the TreeGrid.

**Documentation**: https://blazor.syncfusion.com/documentation/treegrid/editing/template-editing

**Online examples**: https://blazor.syncfusion.com/demos/tree-grid/dialog-editing?theme=bootstrap4

## Key Features

- Demonstrates TreeGrid dialog editing customization using edit templates.
- Configures TreeGrid editing in Dialog mode for record management.
- Replaces the default TreeGrid edit dialog UI with a customized template.
- Uses custom editor controls rendered inside the dialog template.
- Supports add, edit, update, and delete operations through dialog-based editing workflows.
- Demonstrates editing hierarchical records within the TreeGrid component.
- Shows how custom input elements can be integrated into the dialog template.
- Implements template-driven dialog customization rather than relying on the default generated editors.
- `Pages/Index.razor` contains the primary TreeGrid implementation and dialog template configuration.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `CustomizeEditDialog.sln`

3. Restore NuGet packages.
4. Ensure the startup project is:

   `CustomizeEditDialog`

5. Build the solution.
6. Run the project using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the directory containing `CustomizeEditDialog.csproj`.

```bash
dotnet restore
dotnet run
```
## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation for dialog template editing: https://help.syncfusion.com/grid-sdk/blazor/tree-grid/editing/template-editing

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
