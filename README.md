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

**Responsiveness:**

Tested the application across various devices (desktop, tablet, smartphone) to ensure proper responsiveness using browser developer tools and real devices.
Confirmed that all elements resize and reposition correctly according to the device's screen size.

**Browser Compatibility**

The application was tested on the following web browsers to ensure compatibility and consistent user experience:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari
  Each page and feature was tested to ensure no differences in display or functionality across different browsers.

**Mobile Responsiveness**

Mobile responsiveness was tested on the following devices:

- iPhone (iOS)
- Android (Pixel, Samsung Galaxy)
- Tablets (iPad, Galaxy Tab)
  The layout and features adapt well to different screen sizes, with no overlapping or misalignment of elements.

## User Testing

In addition to manual testing by the developer, user testing was carried out by inviting a few users to interact with the app. Based on their feedback, the following improvements were made:

- Improved form input validation to prevent incorrect entries (e.g., negative amounts for expenses).
- Adjusted the visual layout for better readability on smaller screens.
- Added confirmation messages after successful actions like adding expenses or generating reports.
- Issues and Fixes
- During testing, several issues were identified and resolved:

Bug: Expense list did not update automatically after adding a new expense.
Fix: Implemented a real-time update feature to refresh the list once a new expense is added.

Bug: Chart data did not reflect changes immediately after adding new expenses.
Fix: Updated the logic in the chart generation function to redraw the charts whenever new data is added.

Bug: Budget progress bar occasionally displayed inaccurate percentages.
Fix: Corrected the calculations to ensure the progress bar correctly reflects the current budget usage.

## Automated Testing

**Unit Tests:** Basic unit tests were written to check the core functionality of adding expenses and generating reports. These were run using a JavaScript testing framework (e.g., Jasmine or Mocha).

**Integration Testing:** Integration tests were performed to ensure that different components of the app (e.g., adding expenses and updating budgets) work together seamlessly.

## Known Issues

- There is a slight delay when generating large reports with many expenses. This will be addressed in future updates by optimizing the report generation logic.
- On very small screens, the report charts sometimes overflow slightly. This is being worked on in the next release.

## Future Testing

Further testing will be conducted as more features are added to ensure everything works correctly. Automated end-to-end tests may be integrated using tools like Selenium for more thorough cross-browser testing.

## Deployment

The project was deployed using Github Pages. It can be seen [here](https://atpswift.github.io/Expense-Tracker/).

## Contact

For any questions, suggestions, or support, please contact:

Email: guluzianjoseph123@gmail.com
