# SAP UI5 Demo Sorting

In SAP UI5, Sorting the list items can be done on list by adding a declarative sorter to our binding syntax.

### Code Explaination

Refer to [/webapp/view/InvoicesList.view.xml](https://github.com/VaibhavMojidra/SAP-UI5---Demo-Sorting/blob/master/webapp/view/InvoicesList.view.xml "InvoicesList.view.xml")

The `List` control has a `sorter` property that specifies the sorting criteria for the list. In this case, the `sorter` property is set to an object with a single property called `path`. The `path` property specifies the name of the property in the `Invoices` model that should be used for sorting. In this case, the `ProductName` property is used for sorting.

When the list is displayed, the items are sorted in ascending order based on the `ProductName` property. If you want to sort the items in descending order, you can set the `descending` property of the `sorter` object to `true`. For example, to sort the items in descending order based on the `ProductName` property, you can modify the `sorter` property as follows:

```
sorter : {
   path : 'ProductName',
   descending : true
}
```

This will sort the items in descending order based on the `ProductName` property.

---

[![Vaibhav Mojidra - 1.jpeg](https://raw.githubusercontent.com/VaibhavMojidra/SAP-UI5---Demo-Sorting/master/screenshot/1.jpeg "Vaibhav Mojidra")](https://vaibhavmojidra.github.io/site/)