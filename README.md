# Example of removing the gap between the cells in the Syncfusion Blazor HeatMap component

## Overview

This sample demonstrates how to remove the visible gaps between cells in a Syncfusion [Blazor HeatMap](https://www.syncfusion.com/blazor-components/blazor-heatmap-chart). The implementation combines HeatMap cell border customization with SVG rendering settings to eliminate spacing artifacts that may remain even when cell borders are removed. This technique is useful when creating dense HeatMap visualizations that require a seamless appearance between adjacent cells.

## Key Features

- Uses the `SfHeatMap` component to render HeatMap data.
- Binds the HeatMap to a two-dimensional integer array data source.
- Configures `HeatMapCellSettings` with `ShowLabel="true"` to display values within cells.
- Uses `TileType="CellType.Rect"` to render rectangular HeatMap cells.
- Sets `HeatMapCellBorder Width="0"` to remove visible borders between adjacent cells.
- Configures `HeatMapCellBorder Color="White"` in the cell border settings.
- Applies the CSS property `shape-rendering: crispEdges` to the SVG element used by the HeatMap.
- Demonstrates how SVG rendering settings can eliminate residual spacing that may remain after removing cell borders.
- Shows a practical approach for creating a continuous HeatMap appearance without visible gaps.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `SampleBlaz.sln`

3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory containing `SampleBlaz.csproj`.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal output.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to HeatMap appearance customization, visit https://help.syncfusion.com/chart-sdk/blazor/heatmap-chart/appearance.

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
