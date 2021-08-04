# HTML Links, JS Functions, and Intro to CSS Layout

![read04](https://brytdesigns.com/wp-content/uploads/2019/12/html_css_javascript_infographic.png)

# HTML Links

### HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

### HTML links - Syntax.

The HTML < a > tag defines a hyperlink. It has the following syntax:

The most important attribute of the < a > element is the href attribute, which indicates the link's destination.

The link text is the part that will be visible to the reader.

By default, links will appear as follows in all browsers:

+ An unvisited link is underlined and blue
+ A visited link is underlined and purple
+ An active link is underlined and red

### HTML Links - The target Attribute.

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

+ _self - Default. Opens the document in the same window/tab as it was clicked

+ _blank - Opens the document in a new window or tab

+ _parent - Opens the document in the parent frame

+ _top - Opens the document in the full body of the window

#### for more info [click here](https://www.w3schools.com/html/html_links.asp)

## HTML Layout

Page layout is the part of graphic design that deals with the arrangement of visual elements on a page. Page layout is used to make the web pages look better. It establishes the overall appearance, relative importance, and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact.

Page Layout Information:

+ Header: The part of a front end which is used at the top of the page. < header > tag is used to add header section in web pages.

+ Navigation bar: The navigation bar is same as menu list. It is used to display the content information using hyperlink.

+ Index / Sidebar: It holds additional information or advertisements and is not always necessary to be added into the page.

+ Content Section: The content section is the main part where content is displayed.

+ Footer: The footer section contains the contact information and other query related to web pages. The footer section always put on the bottom of the web pages. The < footer > tag is used to set the footer in web pages.

## Functions, Methods, and Objects in JS

### Objects:

In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

### Objects in JavaScript: 

Just as in many other programming languages, can be compared to objects in real life. The concept of objects in JavaScript can be understood with real life, tangible objects.

### You access an object method with the following syntax:

objectName.methodName()

You will typically describe fullName() as a method of the person object, and fullName as a property.

The fullName property will execute (as a function) when it is invoked with ().

### Enumerate the properties of an object :

+ for...in loops This method traverses all enumerable properties of an object and its prototype chain.

+ Object.keys(o) This method returns an array with all the own (not in the prototype chain) enumerable properties' names ("keys") of an object o.

+ Object.getOwnPropertyNames(o) This method returns an array containing all own properties' names (enumerable or not) of an object o.

### Function in JavaScript

Every function in JavaScript is a Function object. See Function for information on properties and methods of Function objects.

To return a value other than the default, a function must have a return statement that specifies the value to return. A function without a return statement will return a default value. In the case of a constructor called with the new keyword, the default value is the value of its this parameter. For all other functions, the default return value is undefined.

The parameters of a function call are the function's arguments. Arguments are passed to functions by value. If the function changes the value of an argument, this change is not reflected globally or in the calling function. However, object references are values, too, and they are special: if the function changes the referred object's properties, that change is visible outside the function

### Defining functions

There are several ways to define functions:

The function declaration (function statement)
There is a special syntax for declaring functions (see function statement for details):

function name([param[, param[, ... param]]]) {
   statements
}

+ name

The function name.

+ param

The name of an argument to be passed to the function.

+ statements

The statements comprising the body of the function.

## 6 Reasons for Pair Programming

1. Greater efficiency

2. Engaged collaboration

3. Learning from fellow students

4. Social skills

5. Job interview readiness

6. Work environment readiness

## Intro to CSS Layout

This article will recap some of the CSS layout features we've already touched upon in previous modules — such as different display values — and introduce some of the concepts we'll be covering throughout this module.

CSS page layout techniques allow us to take elements contained in a web page and control where they are positioned relative to their default position in normal layout flow, the other elements around them, their parent container, or the main viewport/window.  The page layout techniques we'll be covering in more detail in this module are:

+ Normal flow

+ The display property

+ Flexbox

+ Grid

+ Floats

+ Positioning

+ Table layout

+ Multiple-column layout