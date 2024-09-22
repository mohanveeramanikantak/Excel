# 📊 Excel Basics: Files and Formulas

Welcome to the **Excel Basics Repository**! This repository contains examples of basic Excel files and commonly used formulas. Whether you're new to Excel or need a refresher, this guide will help you understand how to work with spreadsheets, manipulate data, and apply essential formulas for various tasks.

---

## 📁 Files in This Repository

- **Basic_Excel_Template.xlsx**  
  A template with basic examples of formatting, adding data, and using formulas.

- **Sample_Sales_Data.xlsx**  
  A dataset showing sales data for demonstration purposes, used in various formula examples.

- **Student_Grades_Calculator.xlsx**  
  An Excel sheet to calculate student grades based on assignment scores, using formulas like `SUM`, `AVERAGE`, and `IF`.

---

## 🔢 Common Excel Formulas

Below are some of the most frequently used Excel formulas to help you get started:

### 1. **SUM**
   **Description**: Adds up a range of numbers.
   ```
   =SUM(A1:A10)
   ```
   This will sum the values in cells A1 through A10.

### 2. **AVERAGE**
   **Description**: Calculates the average of a range of numbers.
   ```
   =AVERAGE(B1:B10)
   ```
   This will calculate the average of the values in cells B1 through B10.

### 3. **IF**
   **Description**: Performs a logical test and returns one value if true and another if false.
   ```
   =IF(C2>50, "Pass", "Fail")
   ```
   If the value in C2 is greater than 50, this will return "Pass"; otherwise, it will return "Fail."

### 4. **VLOOKUP**
   **Description**: Looks for a value in the first column of a range and returns a value in the same row from another column.
   ```
   =VLOOKUP(D2, A2:B10, 2, FALSE)
   ```
   This will look for the value in D2 in the first column of the range A2:B10 and return the corresponding value from the second column.

### 5. **COUNTIF**
   **Description**: Counts the number of cells that meet a given condition.
   ```
   =COUNTIF(A1:A10, ">=50")
   ```
   This will count the number of cells in the range A1:A10 that have values greater than or equal to 50.

### 6. **CONCATENATE (or CONCAT)**
   **Description**: Combines multiple text strings into one.
   ```
   =CONCATENATE(A2, " ", B2)
   ```
   This will combine the values in A2 and B2 with a space between them.

### 7. **MAX/MIN**
   **Description**: Returns the largest (`MAX`) or smallest (`MIN`) number in a range.
   ```
   =MAX(E1:E10)
   =MIN(E1:E10)
   ```

### 8. **TODAY**
   **Description**: Returns the current date.
   ```
   =TODAY()
   ```

### 9. **LEFT/RIGHT**
   **Description**: Extracts characters from a text string, starting from the left (`LEFT`) or right (`RIGHT`).
   ```
   =LEFT(F1, 3)    ' Extracts the first 3 characters from the left of cell F1
   =RIGHT(F1, 2)   ' Extracts the last 2 characters from the right of cell F1
   ```

### 10. **LEN**
   **Description**: Returns the length of a text string.
   ```
   =LEN(G1)
   ```

---

## 📚 Additional Resources

- [Microsoft Excel Documentation](https://support.microsoft.com/excel)
- [Excel Formulas Cheat Sheet](https://www.goskills.com/Excel/Resources/Excel-Formulas-Cheat-Sheet)

---

## 🚀 Getting Started

1. Download or clone this repository to your local machine.
2. Open the `.xlsx` files using Microsoft Excel or any other spreadsheet software like Google Sheets.
3. Explore the provided templates and try out the formulas listed above!

---

## 📝 Contribution

Feel free to contribute to this repository by submitting pull requests with new templates, formulas, or improved documentation. Let's learn Excel together!

---

## 🏷️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy Excel-ing! ✨

