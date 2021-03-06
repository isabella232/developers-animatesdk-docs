## element summary

#### Availability

Flash MX 2004.

#### Description

Everything that appears on the Stage is of the type Element. The following code example lets you select an element:
*var el = fl.getDocumentDOM().getTimeline().layers\[0\].frames\[0\].elements\[0\];*

#### Method summary

The following methods are available for the Element object:

| **Method**                                          | **Description**                                                                            |
|-----------------------------------------------------|--------------------------------------------------------------------------------------------|
| [element.getPersistentData()](../Element_object/element2.md)        | Retrieves the value of the data specified by the ***name*** parameter.                     |
| [element.getPublishPersistentData()](../Element_object/element3.md) | *True* if the specified persistent data is enable for the specified format; otherwise *False*. |
| [element.getTransformationPoint()](../Element_object/element4.md)   | Gets the value of the specified element’s transformation point.                            |
| [element.hasPersistentData()](../Element_object/element5.md)        | Determines whether the specified data has been attached to the specified element.          |
| [element.removePersistentData()](../Element_object/elemen12.md)     | Removes any persistent data with the specified name that has been attached to the object.  |
| [element.setPersistentData()](../Element_object/elemen17.md)        | Stores data with an element.                                                               |
| [element.setPublishPersistentData()](../Element_object/elemen18.md) | Enables or disables publishing of persistent data for a specified format.                  |
| [element.setTransformationPoint()](../Element_object/elemen19.md)   | Sets the position of the element’s transformation point.                                   |

#### Property summary

The following properties are available for the Element object:

| **Property**                         | **Description**                                                                                                                                           |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| [element.depth](../Element_object/element.md)      | Read-only; an integer that has a value greater than 0 for the depth of the object in the view.                                                            |
| [element.elementType](../Element_object/element1.md) | Read-only; a string that represents the type of the specified element.                                                                                    |
| [element.height](../Element_object/element6.md)      | A float value that specifies the height of the element in pixels.                                                                                         |
| [element.layer](../Element_object/element7.md)       | Read-only; represents the [Layer object](../Layer_object/layer_summary.md) on which the element is located.                                                                  |
| [element.left](../Element_object/element8.md)        | Read-only; a float value that represents the left side of the element.                                                                                    |
| [element.locked](../Element_object/element9.md)      | A Boolean value: true if the element is locked; false otherwise.                                                                                          |
| [element.matrix](../Element_object/elemen10.md)      | A [Matrix object](../Matrix_object/matrix_summary.md). The matrix has properties *a, b, c, d, tx,* and *ty. a, b, c,* and *d* are floating- point values; tx and ty are coordinates. |
| [element.name](../Element_object/elemen11.md)        | A string that specifies the name of the element, normally referred to as the Instance name.                                                               |

| **Property**                        | **Description**                                                                                                                                            |
|-------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [element.rotation](../Element_object/elemen13.md)   | An integer or float value between -180 and 180 that specifies the object’s clockwise rotation, in degrees.                                                 |
| [element.scaleX](../Element_object/elemen14.md)     | A float value that specifies the *x* scale value of symbols, drawing objects, and primitive rectangles and ovals.                                          |
| [element.scaleY](../Element_object/elemen15.md)     | A float value that specifies the *y* scale value of symbols, drawing objects, and primitive rectangles and ovals.                                          |
| [element.selected](../Element_object/elemen16.md)   | A Boolean value that specifies whether the element is selected or not.                                                                                     |
| [element.skewX](../Element_object/elemen20.md)      | A float value between -180 and 180 that specifies the *x* skew value of symbols, drawing objects, and primitive rectangles and ovals.                      |
| [element.skewY](../Element_object/elemen21.md)      | A float value between -180 and 180 that specifies the *y* skew value of symbols, drawing objects, and primitive rectangles and ovals.                      |
| [element.top](../Element_object/elemen22.md)        | Read-only; top side of the element.                                                                                                                        |
| [element.transformX](../Element_object/elemen23.md) | A floating-point number that specifies the *x* value of the selected element’s transformation point, within the coordinate system of the element's parent. |
| [element.transformY](../Element_object/elemen24.md) | A floating-point number that specifies the *y* value of the selected element’s transformation point, within the coordinate system of the element's parent. |
| [element.width](../Element_object/elemen25.md)      | A float value that specifies the width of the element in pixels.                                                                                           |
| [element.x](../Element_object/elemen26.md)          | A float value that specifies the *x* value of the selected element’s registration point.                                                                   |
| [element.y](../Element_object/elemen27.md)          | A float value that specifies the *y* value of the selected element’s registration point.                                                                   |

<span id="element.depth" class="anchor"></span>

