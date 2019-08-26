# Custom Numeric Keypad

A custom numeric keypad for entering amount up to two decimal places.  
<br />

## Getting Started
<br />

1. Add a link for JavaScript file in the `<head>` section of your html page.

```
<script src="easy-numpad.min.js"></script>
```
<br />

2. Add another link for the stylesheet in your `<head>` section.
```
<link rel="stylesheet" type="text/css" href="easy-numpad.min.css">
```
<br />

3. Use an `<input>` element of type = `number` and provide a `maxlength` of your choice.
```
<input id="amount" type="number" value="" readonly="true" onclick="show_easy_numpad(this);" maxlength="8">
```
**_Note_:** The maximum number of digits allowed on your keypad would be **maxlength** whole number digits + **2 decimal places** `OR` **maxlength + 1** whole number digits.
<br />

## Features
- Only positive numbers are allowed (as amount cannot be negative). Hence, the `±` key is disabled.
- Maximum number of digits allowed can be customised using the `maxlength` property.
- Decimal values up to only two places are allowed.
<br />

## Design

The design and layout for this keypad was taken from [here](https://www.jqueryscript.net/other/Visual-Numerical-Keyboard-Easy-Numpad.html), although it can be customised.
