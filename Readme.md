<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/ScatterLine2DChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/ScatterLine2DChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D  Scatter Line chart

The following example demonstrates how to create a 2D Scatter Line chart.

### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add a [LineScatterSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.LineScatterSeries2D?p=netframework) object with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection.
