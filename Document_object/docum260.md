## document.removeDataFromSelection()

#### Availability

Flash MX 2004.

#### Usage

document.removeDataFromSelection(name)

#### Parameters

**name** A string that specifies the name of the persistent data to remove.

#### Returns

Nothing.

#### Description

Method; removes persistent data with the specified name that has been attached to the selection.

#### Example

The following example removes from the selection the persistent data named "myData": 

```javascript
fl.getDocumentDOM().removeDataFromSelection("myData");

```
#### See also

[document.addDataToSelection()](../Document_object/documen2.md)
