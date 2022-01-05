# HTML Tables
  - The `<table>` HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

  - Back in the day, tables were used to layout (move content or position content) content.

  - Tables should be reserved for tabular data

  - `<td>` **- Table Data Cell** HTML element defines a cell of a table that contains data. It participates in the table model.
  - `<tr>` Table Rows
  - `<th>` Table Headers
  - `<tbody>`Table body
  - `<thead>`Table headers
  - `<tfoot>`Table footers

  - `rowspan=""` - amount how many rows you want to span
  - `colspan=""` - amount how many columns you want to span

# HTML Forms

 - The form element "represents a document section containing interactive controls for submitting information"
 - The *action* attribute specifies WHERE the form data should be sent.
 - The method attribute specifies which HTTP method should be used.

## Inputs
 - `<input>` - The input element is used to create a variety of different form controls.
 - We have 20+ possible types of inputs, raging from date pickers to checkboxes.
 - The *type* attribute is where the magic happens. Changing *type* dramatically alters the input's behavior and appearance.
 - Input doesn't have a closing tag.
 - **Labels** are essential so get used to using them. Labels link the input and associates the input to the text.
 - The way we connect is by using the **id** attribute, then we use the same value in the **for** attribute in our label.

`<label for="username">Username Input</label>`

`<input type="text" id="username">`

## Buttons
 - Buttons inside of a form will, by default, try to submit the form.
 - You can change the type to "button" which would allow it to behave just like a button. Meaning the button would do nothing until JS specifies what it ought to do.

This also works

`<input type="submit" value="Click Me!">`