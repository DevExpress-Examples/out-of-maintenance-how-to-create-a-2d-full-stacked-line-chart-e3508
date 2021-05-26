<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/LineFullStacked2DChart/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/LineFullStacked2DChart/MainWindow.xaml))
<!-- default file list end -->
# How to create a 2D Full-Stacked Line chart

The following example demonstrates how to create a 2D Full-Stacked Line chart.

### Description

To do this, it is necessary to assign the [ChartControl.Diagram](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartControl.Diagram?p=netframework) property to [XYDiagram2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYDiagram2D?p=netframework), and then add two [LineFullStackedSeries2D](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.LineFullStackedSeries2D?p=netframework) objects with points to the diagram's [Series](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.Diagram.Series?p=netframework) collection. 

Also, this example shows how to add a chart title.
