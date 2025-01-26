# GPA Calculator

## Overview
The GPA Calculator is a web-based tool that allows users to calculate their Grade Point Average (GPA) based on the credit hours and grades of their courses. The tool provides a simple and interactive interface to input course details and instantly compute the GPA.

## Features
- **Dynamic Course Fields**: Generate input fields dynamically based on the number of courses.
- **Grade Selection**: Choose grades from a predefined list (e.g., A+, A, B, etc.).
- **Instant Calculation**: Calculates GPA based on user input with a simple button click.
- **Validation**: Alerts users to invalid or incomplete inputs.

## Technologies Used
- **HTML**: Structure of the web application.
- **CSS**: Styling the layout and appearance.
- **JavaScript**: Handles the dynamic behavior and GPA calculation logic.

## Link to Website
You can view and use the GPA Calculator by visiting this link:  
[GPA Calculator](https://gpa-calculator-jal.vercel.app/)

## Usage Instructions
1. Open the `index.html` file in any modern web browser.
2. Enter the **number of courses** in the provided input field.
3. Fill out the dynamically generated fields for each course:
   - Enter **Credit Hours**: The number of hours assigned to the course.
   - Select **Grade**: The grade received for the course from the dropdown menu.
4. Click the **Calculate GPA** button.
5. The calculated GPA will be displayed at the bottom of the page.

## Grading System
The grades and their corresponding points are as follows:
| Grade  | Points |
|--------|--------|
| A+     | 4.00   |
| A      | 3.75   |
| A-     | 3.50   |
| B+     | 3.25   |
| B      | 3.00   |
| B-     | 2.75   |
| C+     | 2.50   |
| C      | 2.25   |
| C-     | 2.00   |
| D      | 1.50   |
| F      | 0.00   |
| AB     | 0.00   |

## Validation Rules
- **Grades**: Must select a valid grade for each course from the dropdown menu.
- **Credit Hours**: Must enter a positive numeric value for each course.

## Customization
You can customize the application by editing the following:
- **Grades and Points**: Modify the `<option>` elements within the `<select>` dropdown for grades in the HTML.
- **Styling**: Update the CSS section to change the appearance, such as colors, fonts, or layout.
- **Validation Rules**: Adjust the `calculateGPA` function to implement additional validation as needed.

## License
This project is open-source and free to use for educational and personal purposes.

---

Feel free to reach out if you have any suggestions or encounter issues while using the GPA Calculator!
