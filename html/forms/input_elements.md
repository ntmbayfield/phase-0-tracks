#HTML <Input> type
< input type="" > Specifies the input type to display

##Various Input Types
Input Type Text
<input type="text"> defines a one-line text input field.
Example:
form>
  First name:<br>
  <input type="text" name="firstname"><br>
  Last name:<br>
  <input type="text" name="lastname">
</form>

Input Type Password
<input type="password"> defines a password field.
Example:
<form>
  User name:<br>
  <input type="text" name="username"><br>
  User password:<br>
  <input type="password" name="psw">
</form>

Input Type Submit
<input type="submit"> defines a button for submitting form data to a form-handler.  The form-handler is typically a server page with a script for processing input data.  The form-handler is specified in the form's action attribute.
Example:
<form action="/action_page.php">
  First name:<br>
  <input type="text" name="firstname" value="Mickey"><br>
  Last name:<br>
  <input type="text" name="lastname" value="Mouse"><br><br>
  <input type="submit" value="Submit">
</form>

Input Type Checkbox
<input type="checkbox"> defines a checkbox.  Checkboxes let a user select ZERO or MORE options of a limited number of choices.
Example:
<form>
  <input type="checkbox" name="vehicle1" value="Bike"> I have a bike<br>
  <input type="checkbox" name="vehicle2" value="Car"> I have a car
</form>

Input Type Button
<input type="button"> defines a button.
Example:
<input type="button" onclick="alert('Hello World!')" value="Click Me!">

##HTML < input > tag
####Definition and Usage
The < input > tag specifies an input field where the user can enter data.  < input > elements are used within a < form > element to declare input controls that allow users to input data.  An input field can vary in many ways, depending on the type attribute.
Note: The < input > element is empty, it contains attributes only.
Tip: Use the < label > element to define labels for < input > elements.

##HTML < input > type attribute
The type attribute specifies the type of < input > element to display.
The default type is text.  Syntax: < input type="value" >

Value         Description
button        Defines a clickable button (mostly used with a
              JavaScript to activate a script)
checkbox      Defines a checkbox
color         Defines a color picker
date          Defines a date control (year, month and day (no time))
              datetime-local  Defines a date and time control (year, month, day, hour, minute, second, and fraction of a second (no time zone)
email         Defines a field for an e-mail address
file          Defines a file-select field and a "Browse..." button (
              for file uploads)
hidden        Defines a hidden input field
image         Defines an image as the submit button
month         Defines a month and year control (no time zone)
number        Defines a field for entering a number
password      Defines a password field (characters are masked)
radio         Defines a radio button
range         Defines a control for entering a number whose exact
              value is not important (like a slider control). Default range is from 0 to 100
reset         Defines a reset button (resets all form values to
              default values)
search        Defines a text field for entering a search string
submit        Defines a submit button
tel           Defines a field for entering a telephone number
text          Default. Defines a single-line text field (default width
              is 20 characters)
time          Defines a control for entering a time (no time zone)
url           Defines a field for entering a URL
week          Defines a week and year control (no time zone)

##Other Form Tags
< div >
The < div > tag defines a division or a section in an HTML document.  The < div > tag is used to group block-elements to format them with CSS.
Example:  <div style="color:#0000FF">
            <h3>This is a heading</h3>
            <p>This is a paragraph.</p>
          </div>

< fieldset >
The < fieldset > tag is used to group related elements in a form.  The < fieldset > tag draws a box around the related elements.  Tip: The <  legend > tag defines a caption for the < fieldset > element.
Example:  <form>
            <fieldset>
              <legend>Personalia:</legend>
              Name: <input type="text"><br>
              Email: <input type="text"><br>
              Date of birth: <input type="text">
            </fieldset>
          </form>

< button >
The < button > tag defines a clickable button.  Inside a < button > element you can put content, like text or images. This is the difference between this element and buttons created with the < input > element.  Tip: Always specify the type attribute for a < button > element. Different browsers use different default types for the < button > element.
Example: <button type="button">Click Me!</button>
