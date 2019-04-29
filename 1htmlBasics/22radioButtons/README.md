Basic HTML and HTML5: Create a Set of Radio Buttons
You can use radio buttons for questions where you want the user to only give you one answer out of multiple options.

Radio buttons are a type of input.

Each of your radio buttons can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the radio button input with the label element surrounding it.

All related radio buttons should have the same name attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.

Here's an example of a radio button:

<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
It is considered best practice to set a for attribute on the label element, with a value that matches the value of the id attribute of the input element. This allows assistive technologies to create a linked relationship between the label and the child input element. For example:

<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>

Add a pair of radio buttons to your form, each nested in its own label element. One should have the option of indoor and the other should have the option of outdoor. Both should share the name attribute of indoor-outdoor to create a radio group.

Your page should have two radio button elements.
Give your radio buttons the name attribute of indoor-outdoor.
Each of your two radio button elements should be nested in its own label element.
Make sure each of your label elements has a closing tag.
One of your radio buttons should have the label indoor.
One of your radio buttons should have the label outdoor.
Each of your radio button elements should be added within the form tag.