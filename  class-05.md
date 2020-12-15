# CSS

![alt text](https://disenowebakus.net/en/images/articles/learn-css.jpg)

## What is CSS?

### CSS stands for Cascading Style Sheets it describes how HTML elements are to be displayed on screen, paper, or in other media
### CSS saves a lot of work. It can control the layout of multiple web pages all at once, External stylesheets are stored in CSS files

### Why Use CSS?

## CSS Syntax

#### A CSS rule-set consists of a selector and a declaration block:

```
h1{
    color:blue
}
```

##### The selector points to the HTML element you want to style.

##### The declaration block contains one or more declarations separated by semicolons.

##### Each declaration includes a CSS property name and a value, separated by a colon.

##### Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

## CSS Colors:

### Colors in CSS can be specified by the following methods:

1. Hexadecimal colors

#### Example
```
#p1 {background-color: #ff0000;}   /* red */
#p2 {background-color: #00ff00;}   /* green */
#p3 {background-color: #0000ff;}   /* blue */
```
2. RGB colors

#### Example
```
#p1 {background-color: rgb(255, 0, 0);}   /* red */
#p2 {background-color: rgb(0, 255, 0);}   /* green */
#p3 {background-color: rgb(0, 0, 255);}   /* blue */
```

3. Predefined/Cross-browser color names

#### Example
```
#p1 {background-color: blue;}
#p2 {background-color: red;}
#p3 {background-color: coral;}
#p4 {background-color: brown;}
```

4. With the currentcolor keyword

#### Example
```
#myDIV {
  color: blue; /* Blue text color */
  border: 10px solid currentcolor; /* Blue border color */
}
```

## CSS display Property

#### The display property specifies the display behavior (the type of rendering box) of an element.

### Property Values:

1. inline
Displays an element as an inline element (like <span>). Any height and width properties will have no effect.

2. block 
Displays an element as a block element (like <p>). It starts on a new line, and takes up the whole width	

3. none
The element is completely removed	

 


