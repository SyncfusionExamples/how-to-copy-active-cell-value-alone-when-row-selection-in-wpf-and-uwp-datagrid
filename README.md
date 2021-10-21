# How to copy active cell value alone when row selection in WPF DataGrid (SfDataGrid)?

This example illustrates how to copy active cell value alone when row selection in [WPF DataGrid](https://www.syncfusion.com/wpf-ui-controls/datagrid) (SfDataGrid).

All the record contents will be copied to the clioboard by default when the SelectionUnit is set as Row in [WPF DataGrid](https://www.syncfusion.com/wpf-ui-controls/datagrid) (SfDataGrid). You can copy the active cell value alone by using the [SfDataGrid.GridCopyCellContent](http://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.SfDataGrid~CopyGridCellContent_EV.html) event. You can remove tab character from the copied data by overriding the [CopyCell](http://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.GridCutCopyPaste~CopyCell.html) method in [GridCutCopyPaste](http://help.syncfusion.com/cr/cref_files/wpf/Syncfusion.SfGrid.WPF~Syncfusion.UI.Xaml.Grid.GridCutCopyPaste.html) class.

KB article - [How to copy active cell value alone when row selection in WPF DataGrid (SfDataGrid)?](https://www.syncfusion.com/kb/9913/how-to-copy-active-cell-value-alone-when-row-selection-in-wpf-datagrid-sfdatagrid)
