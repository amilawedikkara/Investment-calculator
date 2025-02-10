# Investment Calculator

## Overview
This is a simple web-based **Investment Calculator** that allows users to estimate their investment growth over time based on:
- Initial Investment Amount
- Monthly Contribution
- Number of Years
- Annual Interest Rate (%)

The results are displayed in a table, showing the investment value and total contributions for each year.

## Features
- Dynamic input fields for investment details
- Button to calculate the investment growth
- Table that updates with calculated results
- Dynamic table header that displays the selected interest rate

## Technologies Used
- **HTML**: Structure of the webpage
- **CSS**: Basic styling for the table
- **JavaScript**: Handles user input and performs investment calculations

## How to Use
1. Open `index.html` in a web browser.
2. Enter the **Initial Investment**, **Monthly Contribution**, **Duration in Years**, and **Interest Rate (%).**
3. Click the **"Calculate"** button.
4. The results table will update dynamically with yearly investment values.

## Code Breakdown
### **HTML Structure**
- Input fields for user data
- A button to trigger calculations
- A table to display results

### **JavaScript Functionality**
1. **Retrieve Input Values**: Gets user-entered investment details.
2. **Update Table Header**: Modifies the interest rate in the table dynamically.
3. **Loop Through Years**:
   - Calculates the total savings and investment value each year.
   - Applies annual interest growth.
4. **Update Table Rows**: Appends yearly data dynamically.

## Example Calculation
If you enter:
- Initial Investment: **$1,000**
- Monthly Contribution: **$50**
- Duration: **5 years**
- Interest Rate: **5%**

The script will calculate and display the total investment value and contributions for each year.

## Potential Improvements
- Add **real-time updates** when inputs change (without clicking "Calculate").
- Improve **styling** for a better user interface.
- Add a **graph/chart** to visualize the investment growth over time.

## Author
Developed by Amila Iresh

## License
This project is open-source and can be modified or distributed under the MIT License.

