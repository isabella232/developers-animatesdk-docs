## fill.bitmapPath

#### Availability

Flash CS4 Professional.

#### Usage

fill.bitmapPath

#### Description

Property; a string that specifies the path and name of the bitmap fill in the Library. This property is available only if the value of the [fill.style](../Fill_object/fill9.md) property is "bitmap".

#### Example

The following example sets the fill style of the specified item to a bitmap image in the Library:

```javascript
var fill = fl.getDocumentDOM().getCustomFill();
fill.style = "bitmap";
fill.bitmapPath = "myBitmap.jpg";
fl.getDocumentDOM().setCustomFill(fill);
```
#### See also

[fill.bitmapIsClipped](../Fill_object/fill.md)
