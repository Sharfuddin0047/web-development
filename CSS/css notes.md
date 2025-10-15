🎨 CSS Selectors

Last Updated: 23 Jul, 2025

CSS Selectors are powerful tools used to target HTML elements and apply styles based on their tag, class, ID, attributes, and more. They form the foundation of styling in web development.



🌟 Types of CSS Selectors

\- Basic Selectors: Target elements by tag name, class (.class), or ID (#id).

\- Combinators: Style elements based on their relationship in the DOM (e.g., parent-child, siblings).

\- Group Selectors: Apply the same styles to multiple unrelated elements.

\- Attribute Selectors: Target elements based on attributes and their values.

\- Pseudo-Classes: Style elements based on dynamic states or structural position.

\- Pseudo-Elements: Style specific parts of an element, like the first letter or line.



🔹 Basic Selectors

1\. Universal Selector (\*)

Applies styles to all elements.

\* {

&nbsp;   color: red;

}





2\. Element Selector

Targets all elements of a specific type.

p {

&nbsp;   font-size: 16px;

}





3\. Class Selector (.)

Styles elements with a specific class.

.button {

&nbsp;   background-color: blue;

&nbsp;   color: white;

}





4\. ID Selector (#)

Targets a unique element by ID.

\#header {

&nbsp;   background-color: gray;

}







🔗 Combinator Selectors

1\. Descendant Selector ( )

Targets elements nested inside another.

div p {

&nbsp;   color: red;

}





2\. Child Selector (>)

Targets direct children only.

div > p {

&nbsp;   margin-left: 20px;

}





3\. Adjacent Sibling Selector (+)

Styles the element immediately following another.

h1 + p {

&nbsp;   font-weight: bold;

}





4\. General Sibling Selector (~)

Styles all siblings that follow a specific element.

h1 ~ p {

&nbsp;   font-style: italic;

}







🧩 Attribute Selectors

1\. Presence Selector (\[attr])

Targets elements with a specific attribute.

input\[type] {

&nbsp;   border: 2px solid black;

}





2\. Attribute Value Selector (\[attr="value"])

Targets elements with a specific attribute value.

input\[type="text"] {

&nbsp;   background-color: yellow;

}





3\. Substring Matching (^=)

Matches attribute values that start with a specific string.

a\[href^="https"] {

&nbsp;   color: green;

}





4\. Wildcard Matching (\*=)

Matches attribute values containing a specific substring.

a\[href\*="example"] {

&nbsp;   text-decoration: underline;

}







🎭 Pseudo-Classes

1\. :hover

Applies styles when the user hovers over an element.

a:hover {

&nbsp;   color: red;

}





2\. :focus

Styles elements when they gain focus.

input:focus {

&nbsp;   outline: 3px solid red;

}





3\. :first-child

Targets the first child of a parent.

p:first-child {

&nbsp;   color: brown;

}





4\. :last-child

Targets the last child of a parent.

p:last-child {

&nbsp;   color: green;

}





5\. :not()

Excludes elements from styling.

p:not(.one) {

&nbsp;   color: blue;

}







✨ Pseudo-Elements

1\. ::before

Inserts content before an element.

h1::before {

&nbsp;   content: "★ ";

}





2\. ::after

Inserts content after an element.

h1:active::before {

&nbsp;   content: " ";

&nbsp;   color: orangered;

}





3\. ::first-line

Styles the first line of text in a block.

p::first-line {

&nbsp;   color: red;

}





4\. ::first-letter

Styles the first letter of a block.

p::first-letter {

&nbsp;   color: red;

&nbsp;   font-size: 23px;

}





5\. ::placeholder

Styles the placeholder text in input fields.

input::placeholder {

&nbsp;   font-size: 20px;

&nbsp;   font-family: sans-serif;

&nbsp;   font-weight: 900;

}











