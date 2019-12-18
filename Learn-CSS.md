# CSS

1. Uses a seperate **Stylesheet** called styles.css
Link to it in the **Head** section of HTML page
<link> href="css/styles.css" type="text/css" rel="stylesheet"/>

2. Uses inline rules on html page by placing a <style> element within the <head>

Block | Inline
______|_______
<h1>-<h6>, <p>, <div>|<b>, <i>, <img>, <em>, <span>

## Examples of styles:

Boxes:
Control width & height 
Borders - colors, width, & style
Back Ground - colors & Images
Position within browser window

Text: Typeface, size, color, italics, bold, case

## Selectors

- Selector {
    Declaration goes here
    **Property:** *Value*
}

Universal = * {}
Elements = h1 {}
Class = .classname {}
ID = #idname {}

## Hierarchy

Child elements will inherit their parents properties
More specific selectors will take precedence
last rule applied will take precedence
adding **!** after any property will give it priority

## Color

- RGB Values - (red,green,blue)
- HEX Codes - #FFFFFF hexidecimal values
- Color Names - 147 predefined colors
- Hue - expressed as an angle (0-360)
- Saturation - Expressed as a %
- Lightness - 0%(white) 50%(normal) 100%(black) 
- Alpha - Opacity (Transparency) between 0 - 1.0