## CSS Info

CSS applies rules as to how HTML elements should appear
- A CSS rule contains two parts: a selector and a declaration.  
    - Example:  p {font-family: Arial;}  
        - p is the selector saying that all p elements will have the font Arial
        - The items in the braces is the declaration
- CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon
    - Using the previous example, the font-family is the property
    - Arial is the value of that property

### Color

Foreground color can be specified in three different ways:
1. RGB - These express colors in terms of how much red, green and blue are used to make it up. 
    - For example: rgb(100,100,90)
2. Hex - These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. 
    - For example: #ee3e80
3. Color - Color names There are 147 predefined color names that are recognized by browsers. 
    - For example: DarkCyan

Background color is specified for each block that css recognizes, such as body, header, footer, etc. and sets the color for the background of that block
- Example:  body {background-color: rgb(200,200,200);} 

Opacity - CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).  It is rgba.
- Example:  p.one { background-color: rgb(0,0,0); opacity: 0.5;} p.two { background-color: rgb(0,0,0); background-color: rgba(0,0,0,0.5);} 

HSL - CSS3 also allows you to specify colors as HSL values,  X with an optional opacity value. It is known as HSLA.
- Example: p { background-color: #ffffff; background-color: hsla(0,100%,100%,0.5);}