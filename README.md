# Three Text Fields

## Objectives

- Create an app with multiple text fields
- Respond to user input in text fields
- Conform class to an existing protocol

## Behavior Requirements
### Text Fields
#### Top text field:
- [ ] Should keep a maximum of five characters.
- [ ] Any characters the user enters are acceptable.
- [ ] If the user enters more than five characters in the text field, any additional characters should not be shown in the text field. 
- [ ] The backspace key should work.

#### Middle text field:
- [ ] Should be tied to a switch (use documentation for UISwitch control)
- [ ] When the switch is in the on position, the text field should be editable with any amount of characters allowed.
- [ ] When the switch is in the off position, the text field should not be editable.

#### Bottom text field:
- [ ] Should display a dollar figure with two digits for the pennies, and at least one digit for the dollars.
- [ ] The field should originally display $0.00. 
- [ ] If the user types in five 2's, then the value should progress like this: $0.02, $0.01, $0.12, $1.23, $12.34, and finally $123.45 (assume that the user never backspaces, and that the user only inputs ints into this text field).

## Extra Features
- [ ] If a user enters a backspace, the text field should update appropriately. For example, if the text field currently contains $123.45, and the user enters a backspace, the textfield should be updated to $12.34
- [ ] If the user enters anything but an int, ignore it
- [ ] Change the keyboard to the numeric keyboard for this text field only