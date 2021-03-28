**CSS-Cascading Style Sheets**

CSS allows you to create rules that specify how the content of
an element should appear.

Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).

Different types of selectors allow you to target your
rules at different elements.

Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

CSS rules usually appear in a separate document,
although they may appear within an HTML page.

You can specify any
color in CSS in one of three ways:

* rgb values For example: rgb(100,100,90)
* hex codes For example: #ee3e80
* color names For example: DarkCyan

CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA. The value is a number between
0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15%
opacity). For example: background-color: rgba(0,0,0,0.5);

CSS3 also allows you to specify colors as HSL values, (hue, saturation and lightness) with an optional opacity value (Alpha for transparency). It is known as HSLA.

background-color: hsl(0,0%,78%);}
background-color: hsla(0,100%,100%,0.5);}
