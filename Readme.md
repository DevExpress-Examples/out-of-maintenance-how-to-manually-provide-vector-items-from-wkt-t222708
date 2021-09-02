<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128571717/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T222708)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/SqlGeometryItemStorageExample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/SqlGeometryItemStorageExample/MainWindow.xaml))
<!-- default file list end -->
# How to manually provide vector items from WKT


This example demonstrates how to provide vector items from the SQL Geometry Well-Known Text.


<h3>Description</h3>

To manually provide vector items from WKT, create a <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSqlGeometryItemStoragetopic">SqlGeometryItemStorage</a>&nbsp;object and assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapVectorLayer_Datatopic">VectorLayer.Data</a>&nbsp;property. Then add <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSqlGeometryItemtopic">SqlGeometryItem</a>&nbsp;objects with the&nbsp;specified <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapSqlGeometryItem_WktStringtopic">WktString</a>&nbsp;property to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapSqlGeometryItemStorage_Itemstopic">SqlGeometryItemStorage.Items</a>&nbsp;collection.

<br/>


