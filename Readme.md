# How to manually provide vector items from WKT


This example demonstrates how to provide vector items from the SQL Geometry Well-Known Text.


<h3>Description</h3>

To manually provide vector items from WKT, create a <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSqlGeometryItemStoragetopic">SqlGeometryItemStorage</a>&nbsp;object and assign it to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapVectorLayer_Datatopic">VectorLayer.Data</a>&nbsp;property. Then add <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfMapSqlGeometryItemtopic">SqlGeometryItem</a>&nbsp;objects with the&nbsp;specified <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapSqlGeometryItem_WktStringtopic">WktString</a>&nbsp;property to the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfMapSqlGeometryItemStorage_Itemstopic">SqlGeometryItemStorage.Items</a>&nbsp;collection.

<br/>


