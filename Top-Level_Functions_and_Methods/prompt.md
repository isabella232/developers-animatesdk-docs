## prompt()

#### Availability

Flash MX 2004.

#### Usage

prompt(promptMsg [,text])

#### Parameters

**promptMsg** A string to display in the Prompt dialog box (limited to 256 characters in Mac OS X).

**text** An optional string to display as a default value for the text field.

#### Returns

The string the user typed if the user clicks OK; null if the user clicks Cancel.

#### Description

Method; displays a prompt and optional text in a modal Alert dialog box, along with OK and Cancel buttons.

#### Example

The following example prompts the user to enter a user name. If the user types a name and clicks OK, the name appears in the Output panel.

```javascript
var userName = prompt("Enter user name", "Type user name here"); 
fl.trace(userName);

```
#### See also

[alert()](../Top-Level_Functions_and_Methods/alert.md), [confirm()](../Top-Level_Functions_and_Methods/confirm.md)
