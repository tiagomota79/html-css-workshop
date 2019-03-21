## Description

Create an HTML file and a CSS file that reproduces the following:
![goal](goal.gif)

Use flexbox

## Reference

Your HTML should have the following structure:

```
<!DOCTYPE html>
<html>
   <head>
       <link rel="stylesheet" type="text/css" href="style.css">
   </head>
   <body>
      ...
   </body>
</html>
```

Where style.css is the name of your css file.

Set the body margin to 0 to remove the default 8px margin in Google Chrome

We will be using the **Poppins** font for this exercise.  
Go to google fonts and look for it, follow the instructions.  
You will have to add a `<link>` tag in the head of your HTML file.

The apple icon is in the imgs folder.
You will need to use `display: block` or the icon won't be aligned (inline elements are affected by line-height which is not 0 by default)

The background color for the navbar is `#3a363`

To remove the default underline style on anchor tags you can use `text-decoration: none`

You can use the `href="#"` attribute on `<a>` to make the anchor tags behave like links (with hand cursor). `#` refers to the current page (so the link will just reload the page)

You will need to use the `:hover` pseudo selector on the navbar links and change the opacity.
In order to have a smooth transition for the opacity, you will need to use the `transition` css property.  
Recommended transition time is **0.2s** and easing function is _ease-in-out_

Note - You can use the child selector in your css to apply a style to all your links, e.g.

```
.nav > a {
/* CSS CODE */
}
```

Here is the full list of CSS properties you will need:

```
padding
background
align-items
justify-content
color
margin
font-family
text-decoration
transition
display
opacity
:hover
```
