# Expense Tracker Web Application

## Purpose

The **Expense Tracker** web application is designed to help users manage their personal finances by tracking expenses, setting budgets, and generating reports. It empowers users to take control of their spending habits, visualize financial data, and make informed decisions about their finances.

## Value to Users

- **Organized Financial Data**: Users can easily record and categorize their expenses, ensuring they have a clear overview of where their money is going.
- **Budget Management**: By setting budgets for different categories, users can keep their spending in check and avoid overspending.
- **Insightful Reports**: The application provides users with detailed reports, helping them identify spending patterns, trends, and areas where they can save money.
- **User-Friendly Interface**: The application is designed to be intuitive and accessible, making it easy for users of all technical levels to manage their finances.
- **Cross-Device Compatibility**: The responsive design ensures that users can access the application from any device, whether it's a desktop, tablet, or smartphone.

## Features

1. **Add and View Expenses**
   **Description**: Users can add new expenses by entering details such as the expense name, amount, and category. The application displays all recorded expenses in a list format.
   **Value**: Provides a centralized way to record and track all financial transactions, ensuring users have a clear and organized overview of their spending.

<img width="941" alt="ss1" src="https://github.com/user-attachments/assets/45ddd6f9-e5fb-4aeb-b6ac-d28de5b440b4">

<img width="944" alt="ss2" src="https://github.com/user-attachments/assets/a87a31ae-2c1b-4401-b250-20b281f134cf">

2. **Budget Management**
   **Description**: Users can set budgets for different spending categories and track their spending against these budgets.
   **Value**: Helps users to control their spending by setting limits and visualizing how much they have left to spend.

<img width="944" alt="ss3" src="https://github.com/user-attachments/assets/02847fcd-62de-4d95-aa58-d5c6694e96a7">

<img width="938" alt="ss4" src="https://github.com/user-attachments/assets/f6573f50-c200-4c37-af83-82ee68979862">

4. **Report Generation**
   **Description**: The application generates detailed reports based on the user's expenses, displaying trends and patterns in their spending habits.
   **Value**: Offers users valuable insights into their financial behaviour, allowing them to make informed decisions to improve their financial health.

<img width="945" alt="ss5" src="https://github.com/user-attachments/assets/606ec042-a965-4c0c-9f14-d5b978cacf1d">

<img width="937" alt="ss6" src="https://github.com/user-attachments/assets/268afddf-e7c3-464e-b7cb-43dc52fb01cc">

## How to Clone

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/expense-tracker.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd expense-tracker
   ```

3. **Open the Application**:

   Open index.html in a web browser.

## Deployment Procedure

1.  Pushed the code to the main branch (or master if using an older setup).
2.  Go to your GitHub repository settings.
3.  Scroll down to the "GitHub Pages" section.
4.  Set the source branch to main and the folder to /root or /docs.
5.  Save and wait for GitHub to deploy your site. The site was live at https://atpswift.github.io/expense-tracker/.

## Attribution

**Chart.js**: Used for generating charts in the reports. The library is included in the reports.js file, and the following comment is placed at the top of the relevant section:

Chart.js - https://www.chartjs.org/
Used to create dynamic charts in the reports section

**Logo**: The logo used was taken from [Vecteezy](https://www.vecteezy.com/)

**Font**: The font used is Roboto, taken from [Google Fonts](https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap)

## Code Structure

HTML: The HTML files (index.html, budgets.html, reports.html) are organized with clear sections and comments to improve readability. Each file starts with a <!DOCTYPE html> declaration and is structured with a head section containing meta information and links to stylesheets, followed by a body section that contains the content.

CSS: All CSS code is placed in external files located in the assets/css directory. These files are linked in the head section of the HTML files.

JavaScript: All JavaScript code is placed in external files located in the js directory. These files are linked just above the closing </body> tag in the HTML files.

## Code Sections and Readability

**Consistent Indentation**: All code is consistently indented using 2 spaces for HTML, CSS, and JavaScript. This ensures that the code is easy to read and maintain.

**Commenting**: Sections of the code are clearly defined with comments, making it easy to navigate and understand the purpose of each block of code.

## Directory Structure:

assets/: Contains all static files such as CSS, JavaScript, and images.
css/: Contains the stylesheet.
js/: Contains all JavaScript files.
images/: Contains all image files.
screenshots/: Contains screenshots used in this README.md file.

**Directory structure**:

```
├── assets
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── scripts.js
│   ├── images
│   │   └── logo.png
│   ├── screenshots
│       └── add-expense.png
│       └── manage-budgets.png
│       └── generate-reports.png
├── index.html
├── budgets.html
├── reports.html
├── README.md
```

## Testing and Validation

## Code Validation

All code has been validated using the following tools to ensure it meets current web standards:

HTML: The HTML files were validated using [W3C HTML Validator](https://validator.w3.org/). All pages were tested for syntax errors and corrected accordingly.
CSS: The CSS was validated using [W3C Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/). Any errors or warnings were reviewed and fixed.
JavaScript: The JavaScript files were validated using [JSHint](https://jshint.com/) to ensure proper syntax and avoid potential issues.
Testing

## Functionality Testing

Manual testing was carried out to ensure all functionality works as expected. Below is a list of actions tested in the application:

**Add and View Expenses:**

Entered different expense details (name, amount, and category) to ensure the data was saved and displayed correctly.
Verified that the expenses appear in the list with accurate formatting and no duplication issues.

**Budget Management:**

Tested the budget-setting functionality by setting budgets for different categories.
Ensured that the remaining budget updates correctly after adding new expenses.

**Report Generation:**

Generated reports based on expenses over various periods (e.g., weekly, monthly).
Verified that reports display accurate data in the form of charts and text.

## Testing

Testing the application was carried out in multiple stages, focusing on functionality, site responsiveness, code validation, and bug handling. Below is a detailed breakdown of the testing performed.

### 1. Manual Testing

**Manual testing** was performed on each section of the site to ensure every interactive element (buttons, forms, navigation links) works as intended. Tests were conducted for both the "happy path" (correct inputs) and "bad path" (incorrect inputs) scenarios.

| Feature Tested   | Expected Behavior                          | Test Performed                                             | Result                                               | Fixes Needed (if any) |
| ---------------- | ------------------------------------------ | ---------------------------------------------------------- | ---------------------------------------------------- | --------------------- |
| Add Expense Form | Add a new expense with correct data inputs | Entered name, amount, and category; submitted form         | Successfully added the expense and updated the list  | None                  |
| Add Expense Form | Prevent empty or negative inputs           | Entered negative/empty values, form should reject          | Form displayed validation message                    | None                  |
| Budget Setting   | Set budget for a category                  | Entered a budget for 'Food'; submitted                     | Budget added successfully, remaining balance updated | None                  |
| Budget Exceeded  | Exceed the set budget for a category       | Added expenses more than set budget                        | Notification displayed for exceeding the budget      | None                  |
| Navigation Links | Redirect to the respective sections        | Clicked on 'Reports' and 'Budgets' in the navbar           | Redirected to the correct section                    | None                  |
| Chart Generation | Generate reports based on expenses         | Viewed charts after adding expenses for several categories | Reports displayed accurate data visually             | None                  |

**Example Screenshot:**
<img width="751" alt="image (4)" src="https://github.com/user-attachments/assets/e416785f-d0e1-449e-9086-8e061b7b578b">
<img width="755" alt="image (3)" src="https://github.com/user-attachments/assets/69348cca-f046-4848-857a-ea3706b8c1c1">
<img width="718" alt="image (5)" src="https://github.com/user-attachments/assets/9121cf3c-c4c1-4a7c-b85f-a3a1a84446ec">
<img width="716" alt="image (6)" src="https://github.com/user-attachments/assets/69353b2d-7f8e-4424-bbb0-25ae6dcfcf6d">
<img width="728" alt="image (7)" src="https://github.com/user-attachments/assets/7921bdac-13e5-499c-8d86-6c3ce6645180">


### 2. Testing Site Responsiveness

**Responsiveness** was tested across various devices to ensure that the design adapts to different screen sizes without any layout issues. The tool [Responsive Design Checker](https://responsivedesignchecker.com/) was used for the following tests:

| Device Type            | Screen Size Tested | Expected Outcome                                       | Result                                                      |
| ---------------------- | ------------------ | ------------------------------------------------------ | ----------------------------------------------------------- |
| Mobile (iPhone 12 Pro) | 390x844            | All elements resize appropriately, no overflow issues  | Layout worked perfectly, navigation menu adapted for mobile |
| Tablet (iPad Pro)      | 820x1180           | Proper display of elements, charts resized dynamically | Charts and layout were responsive without overlap           |
| Desktop (1920x1080)    | Full-screen view   | Large charts and expense list fully visible            | Works as expected                                           |

**Example Screenshot:**
<img width="448" alt="image" src="https://github.com/user-attachments/assets/b70754c2-59c2-4268-91b0-9f39ae063b34">
<img width="410" alt="image (1)" src="https://github.com/user-attachments/assets/5b107ee1-520a-4586-9ce8-8b5c60b8bb52">
<img width="704" alt="image (2)" src="https://github.com/user-attachments/assets/655c682d-0556-458b-9b94-915f29c3bcc6">


### 3. Code Validation

All code (HTML, CSS, JavaScript) was validated using online validation tools to ensure compliance with web standards.

- **HTML Validation:** [W3C Validator](https://validator.w3.org/) - No major issues were found, but a few warnings regarding accessibility were addressed.
- **CSS Validation:** [W3C Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/) - Minor styling issues were flagged, which were fixed by correcting certain `media queries`.
- **JavaScript Validation:** [JSHint](https://jshint.com/) - Some syntax warnings were resolved, including missing semicolons.

### 4. Testing of User Stories/Features

**Feature**: Add Expense

- **Expected**: Users can add a new expense by providing a name, amount, and category. The new expense should appear in the list and reflect in the budget report.
- **Test**: Added an expense with valid data, clicked on the 'Add Expense' button.
- **Result**: Expense was successfully added, and the budget updated accordingly.

**Feature**: Generate Reports

- **Expected**: Users can generate visual reports based on their expense data.
- **Test**: Navigated to the 'Reports' section after adding multiple expenses.
- **Result**: Report charts generated accurately, displaying all relevant data.

### 5. Bug Documentation and Resolution

During testing, the following bugs were encountered:

| Bug Description                                                                 | Resolution Steps                                                                                              |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Bug**: Expense list did not refresh automatically after adding a new expense. | **Fix**: Implemented real-time refresh functionality using JavaScript to reload the list after each addition. |
| **Bug**: Budget progress bar showed incorrect percentages.                      | **Fix**: Updated the calculation logic for the progress bar to ensure accuracy.                               |
| **Bug**: Chart data not updated after expenses were added.                      | **Fix**: The chart generation function was adjusted to trigger on each update to the expenses.                |

### 6. Documentation of Open Bugs

Although most issues have been resolved, there are some minor open bugs:

- **Bug**: Report generation has a slight delay when there are too many expenses. This issue will be optimized in a future release.
- **Bug**: On very small screens (e.g., older mobile devices), some charts occasionally overflow. This will be fixed with a more flexible layout in the next update.

## Deployment

The project was deployed using Github Pages. It can be seen [here](https://atpswift.github.io/portfolio-2-final/).

## Contact

For any questions, suggestions, or support, please contact:

Email: guluzianjoseph123@gmail.com


