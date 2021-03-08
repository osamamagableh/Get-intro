# Summary of CH10 + CH11

**CSS Associates Style rules with HTML elements**

CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration

1. selector: indicate which element the rule applies to.
The same rule can apply to more than one element if you separate the element names with commas.

2. declaration: indicate how the elements referred to in the selector should be styled.
Declarations are split into two parts (a property and a value), and are separated by a colon.

**CSS Properties Affect How El ements Are Displayed**

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that
element should look.

* Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that
indicate what these elements should look like).

* Different types of selectors allow you to target your rules at different elements.

* Declarations are made up of two parts: the properties of the element that you want to change, and the values
of those properties. For example, the font-family property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

* CSS rules usually appear in a separate document,
although they may appear within an HTML page.

# Color

**Foreground Color**

color :

The color property allows you to specify the color of text inside an element. You can specify any
color in CSS in one of three ways:

1. rgb values :

These express colors in terms of how much red, green and blue are used to make it up. 
For example: rgb(100,100,90)

2. hex codes :

These are six-digit codes that represent the amount of red, green and blue in a color,
preceded by a pound or hash (#)  sign. For example: #ee3e80

3. color names :

There are 147 predefined color names that are recognized by browsers.
For example: DarkCyan

**background Color :**

body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}

**Contrast**

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

- Low Contrast:

Text is harder to read when there is low contrast between background and foreground colors.

- Medium Contrast:

For long spans of text, reducing the contrast a little bit improves readability.

- High Contrast :

Text is easier to read when there is higher contrast between background and foreground colors.

*to select color i can use* 

1- name ofcotor

2- hexadecimal 

3a - rgb 

3b - rgba -> 

hsl (hue , saturation , lightness)

hue -> color dgree (0 - 360 )
saturation -> persantage 
lightness-> white %



