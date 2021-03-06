## document.setFilters()

#### Availability

Flash 8.

#### Usage

document.setFilters(filterArray)

#### Parameters

**filterArray** The array of filters currently specified.

#### Returns

Nothing.

#### Description

Method; applies filters to the selected objects. Use this method after calling document.getFilters() and making any desired changes to the filters.

#### Example

The following example gets the filters on the selected object and sets the blurX property for all Blur filters to 50:

```javascript
var myFilters = fl.getDocumentDOM().getFilters();
for (i=0; i < myFilters.length; i++) {
if (myFilters[i].name == "blurFilter")
{
     myFilters[i].blurX = 50;
}
}
fl.getDocumentDOM().setFilters(myFilters);

```
#### See also

[document.addFilter()](../Document_object/documen3.md), [document.getFilters()](../Document_object/docume79.md), [document.setFilterProperty()](../Document_object/docum520.md), [Filter object](../Filter_object/filter_summary.md)
