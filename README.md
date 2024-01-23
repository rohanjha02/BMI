# BMI

Sure, let me describe how the entire website works:

HTML (index.html):
- The HTML file provides the structure of the webpage. It includes a form with input fields for weight and height, a button to calculate BMI, and a div to display the result.
- The script.js file is linked to handle the functionality using JavaScript.
- The styles.css file is linked for styling the webpage.

CSS (styles.css):
- Styles have been added to make the webpage visually appealing.
- The body is styled to have a gradient background.
- The calculator container is styled with a white background, padding, border-radius, and box-shadow to create a card-like appearance.
- Input fields, labels, and buttons are styled for a clean and modern look.
- The result section is styled with a margin and a bold font.

JavaScript (script.js):
- The calculateBMI() function is called when the "Calculate BMI" button is clicked. It retrieves the values of weight and height from the input fields.
- If either the weight or height is not provided, an alert is shown, and the function returns without further calculations.
- The BMI is calculated using the formula BMI = weight / (height^2), where height is converted to meters by dividing it by 100. The result is rounded to two decimal places.
- The displayResult() function takes the calculated BMI and displays it along with the BMI category in the result div. The BMI category is determined using the getBMICategory() function.
- The getBMICategory() function returns a category such as "Underweight," "Normal weight," "Overweight," or "Obese" based on the BMI value.

Overall Flow:
1. The user enters their weight and height in the input fields.
2. When the "Calculate BMI" button is clicked, the calculateBMI() function is called.
3. The BMI is calculated and displayed in the result div along with the BMI category.
4. The webpage provides a visually appealing and centered design, making it user-friendly.

This website serves as a basic BMI calculator with a clean and modern user interface. Users can input their weight and height, click the button, and receive their BMI and BMI category as a result.
