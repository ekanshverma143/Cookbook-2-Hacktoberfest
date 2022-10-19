# HTML FORMS
An HTML form is used to collect user input. The user input is most often sent to a server for processing
### The `<form>` Element
The HTML `<form>` element is used to create an HTML form for user input:
```
<form>
.
form elements
.
</form>
```
The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

All the different form elements are covered in this chapter: HTML Form Elements.
### The <input> Element
The HTML `<input>` element is the most used form element.
An `<input>` element can be displayed in many ways, depending on the type attribute.
Here are some examples:
![image](https://user-images.githubusercontent.com/97960380/196786058-3d97ee0c-8e5f-4d73-afc2-a4ae20ca8ca6.png)
### Text Fields
The `<input type="text">` defines a single-line input field for text input.
```
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```
### The `<label>` Element
Notice the use of the `<label>` element in the example above.

The `<label>` tag defines a label for many form elements.

The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The `<label>` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.

The for attribute of the `<label>` tag should be equal to the id attribute of the `<input>` element to bind them together.
### Radio Buttons
The `<input type="radio">` defines a radio button.
Radio buttons let a user select ONE of a limited number of choices.
```
<p>Choose your favorite Web language:</p>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```
### Checkboxes
The `<input type="checkbox">` defines a checkbox.
Checkboxes let a user select ZERO or MORE options of a limited number of choices
```
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```
### The Submit Button
The `<input type="submit"> `defines a button for submitting the form data to a form-handler.

The form-handler is typically a file on the server with a script for processing input data.

The form-handler is specified in the form's action attribute.
### Refrences for more Info
[Html forms](https://www.w3schools.com/html/html_forms.asp)

