[Back to Home](README.md)

# Read 05

## CSS

### What is CSS

CSS is short for Cascading Style Sheets. CSS allows the developer to create rules that style andcontrol the HTML elemetns and the conetent inside thsese elements. CSS can be appear in three different places:

* Inline: The style is be added inside the opening tag of the element.
* Interna: The style is be added in `<style>` tag which is be added into the `<head>` tag.
* External: The style is added into a seperate document with `.css` extention ad linked to the desired html document.

The declaration of the css is made up of two parts: the properties of the element such as `color` or `width`. and the values of those properties. those properties and values should be associated with selectors such as tag names, classes, and IDs.

Example on how to declare a CSS for an element:

```
p {
    color: red;
}
```

### CSS Colors

Developers can specify the color property in three main ways:

* `RGB` Values: Values for red, green and blue are expressed as numbers between 0 and 25
* `HEX` Values: Represent values of red, green and blue in hexadecimal code.
* `Color` Names Predefined names of colors.

Although, these are more ways to specify the color property in CSS. `rgba` is the same as RGB but with the addition of another value that indicates `opacity`. Another way to do that was introduced in CSS3 is called `hsl` which is short for Hue, Saturation and Lightness. The value of the property starts with the letters hsl followed by individual values between parentheses for Hue as a value between 0 and 360, Saturation and Lightness expressed as a persentage value. Similar to `rgb`, `hsl` can have also have opacity value added to it to become `hsla`.

In The table below, you will find an example on how to specify the value of the color property using every way that was mentioned above.

| Coloring Way | Example |
|---|---|
| `rgb` | `color: rgb(255,99,71);` |
| `hex` | `color: #FF6347;` |
| `color name` | `color: tomato;` |
| `hsl` | `color: hsl(9, 100%, 64%);`|

[Back to Home](README.md)
