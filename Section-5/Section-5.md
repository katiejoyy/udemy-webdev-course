# HTML Tables
### What are tables?
- Tables are structured sets of data made up of rows and columns. They can be a great way of displaying data clearly.

### Early usage
- In the early days of the web, tables were commonly used to create page layouts. Today you should only use the table element when you are creating an actual data table.

### Lots of elements!
- To create a table, you'll use 5 -10 different elements! It can be tricky to remember them all but dont panic!

## Table elements
- <td> element defines a cell of a table that contains data. It participates in the table model.

- <tr> element defines a row of cells in a table. The row's cells can then be established using a mix of <td> and <th> elements.

- <th> element defines a cell as header of a group of table cells. The exact nature of this group is defined by the scope and headers attributes.

- <tbody> encapsulates a set of table rows, indicating that they comprise the body of the table

- <colspan> attribute defines the number of columns a cell should span

- <rowspan> attribute defines the number of rows a cell should span

# HTML forms
- The<form> element itself is a shell or container that doesnt have any visual impact
- we then fill the form with a collection of inputs, checkboxes, buttons, etc

## form
- The form element "represents a document section containing interactive controls for submitting information"
- The action attribute specifies WHERE the form data should be sent.
- The method attribute specifies which HTTP method shoud be used (dont worry about this for now)

## <input>
- The input element is used to create a variety of different form controls.
- We have 20+ possible types of inputs ranging from data pickets to checkboxes.
- The type of attribute is where the magic happens. Changing type dramatically alters the inputs's behavior and appearance.

- The HTML <input> element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The <input> element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.

### Label
- The HTML <label> element represents a caption for an item in a user interface.

### Button
- The HTML <button> element represents a clickable button, used to submit forms or anywhere in a document for accessible, standard button functionality. By default, HTML buttons are represented in a style resembling the platform the user agent runs on, but you can change buttons appearance with CSS.

## Checkbox
- <input> elements of type checkbox are redendered by default as boxes that are checked (ticked) when activated, like you might see in an offical government paper form. The exact appearance depends upon the operating system configuration under which the browser is running. Generally, this is a square but it may have rounded corners. A checkbox allows you to select single vaules for submission in a form. 

## Radio
- <input> elements of type radio are generally used in radio groups- collections of radio buttons describing a set of related options. Only one radio button in a given group can be selected at the same time. Radio buttons are typically rendered as small circles, which are filled or highlighted when selected.

## Select
- The HTML <select> element represents a control that provides a menu of options.