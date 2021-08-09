# Problem Domain, Objects, and the DOM

## What are Object literals in JavaScript?

More than one interviewer has asked me this question for front-end positions. If you have done any kind of JavaScript development, you have used an object literal at some point. I’ll explain and provide some sample code.

## What are Object literals in JavaScript?

More than one interviewer has asked me this question for front-end positions. If you have done any kind of JavaScript development, you have used an object literal at some point. I’ll explain and provide some sample code.

---

 var greeting = {

    fullname: "Michael Jackson",
    greet: (message, name) => {
        console.log(message + " " + name + "!!");
    }
}; 

---

Here’s the snippet to use the object we just created to log the fullname and call the greet function with the fullname value.

What the Document Object Model is
The Document Object Model is a programming API for documents. The object model itself closely resembles the structure of the documents it models. For instance, consider this table, taken from an HTML document:

      <TABLE>
      <ROWS> 
      <TR> 
      <TD>Shady Grove</TD>
      <TD>Aeolian</TD> 
      </TR> 
      <TR>
      <TD>Over the River, Charlie</TD>
      <TD>Dorian</TD> 
      </TR> 
      </ROWS>
      </TABLE>

In the Document Object Model, documents have a logical structure which is very much like a tree; to be more precise, it is like a "forest" or "grove" which can contain more than one tree. However, the Document Object Model does not specify that documents be implemented as a tree or a grove , nor does it specify how the relationships among objects be implemented in any way. In other words, the object model specifies the logical model for the programming interface, and this logical model may be implemented in any way that a particular implementation finds convenient. In this specification, we use the term structure model to describe the tree-like representation of a document; we specifically avoid terms like "tree" or "grove" in order to avoid implying a particular implementation. One important property of DOM structure models is structural isomorphism: if any two Document Object Model implementations are used to create a representation of the same document, they will create the same structure model, with precisely the same objects and relationships.