# Numeric_Methods
1. What I Built
I built a simple web-based Numeric Formatter & Validator tool that demonstrates how different JavaScript Number methods work.
The webpage allows users to format numbers as money, show significant digits, convert to scientific notation, safely parse inputs, check safe integers, and perform EPSILON-aware addition.
Each feature has its own input box, button, and output section.

2.Technologies Used
HTML:
I used:
<input> for taking user values
<button> for triggering each numeric operation
<div>, <section>, <h1>, <h2> for structuring the page semantically
These tags make the layout clear and easy to read.
CSS:
I used styling properties like:
padding, margin → better spacing
background-color, box-shadow → card-like look
border-radius → smooth rounded corners
font-family → clean and readable text
These help make the UI simple, neat, and user-friendly.
JavaScript:
I used:
Number methods like toFixed(), toPrecision(), toExponential()
Number utilities like Number.isFinite(), Number.parseInt(), Number.isSafeInteger(), Number.EPSILON
DOM access (document.getElementById) for interactivity
JavaScript adds all the required numeric logic and updates the output in real time.
3. How to Run the Project
Download or copy all project files.
Open index.html in any modern browser (Chrome, Firefox, Edge).
Enter values and click the buttons to see results immediately.
4. Assumptions & Limitations
Works only with numeric or numeric-like inputs (e.g., "42px" is valid, "hello" becomes NaN).
Uses JavaScript’s default number formatting — scientific notation may appear automatically.
EPSILON correction is limited to integer rounding and two-decimal rounding.
The interface is simple and not optimized for mobile screens.
The tool is purely educational and not intended as a full finance-grade library.



