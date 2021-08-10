# Forms and JS Events

## HTML Forms

### The < input > Element

The HTML < input > element is the most used form element.

An < input > element can be displayed in many ways, depending on the type attribute.

Here are some examples:

| Type | Description |
| ------------ | ------------- |
| < input type="text" > | Displays a single-line text input field |
| < input type="radio" > | Displays a radio button (for selecting one of many choices) |
| < input type="checkbox" > | Displays a checkbox (for selecting zero or more of many choices) |
| < input type="submit" > | Displays a submit button (for submitting the form) |
| < input type="button" > | Displays a clickable button |

### The < form > Element
The HTML < form > element is used to create an HTML form for user input. The < form > element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

## Lists in HTML

We use lists whenever we need to list items that are related somehow. A List can be used for cited works, numbered tutorial steps, navigation menus, and many, many other things. I'm sure you are familiar with bullet points from MS Word and other similar programs. There are 3 types of lists in HTML.

### 1. Unordered list

The first type is < ul >, which stands for Unordered List. Items in it are unindexed and are displayed as bullet points as default. Although the list is seen as unordered, the order of items is kept when displayed in a browser. < ul > is a paired tag that wraps list items.

### 2. Ordered list

Unlike unordered lists, items in ordered lists are ordered using a key. All the key is, is a priority or sequence of events. Its syntax is exactly the same as that of unordered lists. We use the < ol > tag to wrap < li > list items.

## Define an HTML Table

The < table > tag defines an HTML table.

Each table row is defined with a < tr > tag. Each table header is defined with a < th > tag. Each table data/cell is defined with a < td > tag.

By default, the text in < th > elements are bold and centered.

By default, the text in < td > elements are regular and left-aligned.

## JavaScript Events

HTML events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can "react" on these events.

## What can JavaScript Do?

### Event handlers can be used to handle and verify user input, user actions, and browser actions:

- Things that should be done every time a page loads
- Things that should be done when the page is closed
- Action that should be performed when a user clicks a button
- Content that should be verified when a user inputs data

### Many different methods can be used to let JavaScript work with events:

- HTML event attributes can execute JavaScript code directly
- HTML event attributes can call JavaScript functions
- You can assign your own event handler functions to HTML elements
- You can prevent events from being sent or being handled