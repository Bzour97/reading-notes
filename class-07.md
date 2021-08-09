# Object-Oriented Programming, HTML Tables

## Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

Model epic fails videos
Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.

Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.

## Tables in HTML

### HTML tables allow web developers to arrange data into rows and columns.

Define an HTML Table

The < table > tag defines an HTML table.

Each table row is defined with a < tr > tag. Each table header is defined with a < th > tag. Each table data/cell is defined with a < td > tag.

By default, the text in < th > elements are bold and centered.

By default, the text in < td > elements are regular and left-aligned.

## Functions, Methods, and Objects

The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Read more about the this keyword at JS this Keyword.

### JavaScript Methods

JavaScript methods are actions that can be performed on objects.
A JavaScript method is a property containing a function definition.

| Property | Value |
| ------------ | ------------- |
| firstName | Ahmad |
| lastName | Bzour |
| Age | 24 |

### Methods are functions stored as object properties.

### FunctionS 

A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

- The name of the function.
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, {...}.