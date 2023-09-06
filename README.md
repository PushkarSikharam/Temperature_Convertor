![Screenshot (31)](https://github.com/PushkarSikharam/Temperature_Convertor/assets/143738056/71b3cb8a-f4b4-45f8-8edd-d88c916a51f3)
![Screenshot (30)](https://github.com/PushkarSikharam/Temperature_Convertor/assets/143738056/95d95b5f-f132-452e-89cc-687d449a4631)
# Temperature_Convertor
This is used to convert the temperature from Celsius to Fahrenheit and vice versa.

Algorithm:
1.Initialize the HTML structure:
a.Create an HTML document with the <!DOCTYPE html> declaration.
b.Define the document's language as English (en).
c.Set up the document's head section with metadata, including character encoding and viewport settings.
d. Give the page a title, "Temperature Converter."

2. Create a CSS style section:
a.Define styles for various elements of the page, including fonts, background image, container styles, and input elements.

3.Build the body of the page:
a. Create a body element.
b. Set the background image for the page and style it.
c. Center the content both horizontally and vertically using flexbox.

4. Create a container div:
a. Inside the body, create a container div with a semi-transparent white background and rounded corners.
b. Add padding to the container and center its content.

5.Create the "Temperature Converter" header:
a. Add an <h1> element with the text "Temperature Converter" to the container.

6.Create two temperature conversion sections:
a. Create two divs with the class "converter" inside the container.
b. Each div contains a label, an input field, and a conversion button.
c. The first div is for converting from Celsius to Fahrenheit, and the second div is for converting from Fahrenheit to Celsius.

7. Define styles for specific elements:
a. Style the header and labels with appropriate fonts and colors.
b. Style input fields and buttons with padding, borders, and backgrounds.
c. Apply specific styles to the Fahrenheit input field, giving it a different background color.

8.  Display the conversion result:
a.Add an empty <div> element with the id "result" to the container. This element will display the conversion result.

9. Add JavaScript code:
a. Define two JavaScript functions, convertToCelsius() and convertToFahrenheit().
b. In convertToCelsius(), retrieve the Fahrenheit value from the input field, convert it to Celsius, display the result, and clear the Fahrenheit input field.
c. In convertToFahrenheit(), retrieve the Celsius value from the input field, convert it to Fahrenheit, display the result, and clear the Celsius input field.
d. Update the result displayed in the "result" <div> based on the conversion.
