## Description

Create an HTML file and a CSS file that reproduces the following:
![goal](goal.gif)

It does not need to be pixel perfect

## Submission

It will automatically be submitted the next time you push.

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

We will be using the **Poppins** font for this exercise.
Go to google fonts and look for it, follow the instructions.
You will have to add a link tag in the head of your HTML file.

The apple icon is in the imgs folder.
You will need to use `display: block;` for the `<img>` element, otherwise it will default to `display: inline-block` which adds some extra space and the icon won't be aligned (inline elements are affected by line-height which is not 0 by default).

Background color: `#3a3633`  
To remove the default underline style on anchor tags you can use `text-decoration: none`

You will need to use the `:hover` pseudo selector on the navbar links and change the opacity  
In order to have a smooth transition for the opacity, you will need to use the `transition` css property.  
Recommended transition time is **0.2s** and easing function is _ease-in-out_
