
# Advanced Mortgage Analysis

**Advanced Mortgage Analysis** is a web-based application designed to calculate mortgage payments with detailed analysis and interactive visualizations. This tool is ideal for homeowners, real estate professionals, and anyone seeking a clear breakdown of their mortgage terms.

---

## Features

### Mortgage Calculator:
- Calculate **Base Monthly Payments** based on:
  - Home Price
  - Down Payment (in **dollars** or **percentage**)
  - Amortization Period (Years)
  - Interest Rate
  - Compounding Method (**Monthly** or **Semi-Annual**)
- Includes optional inputs for **Property Tax**, **Condo Fees**, and **Other Costs**.

### Results Summary:
- Provides a **comprehensive table** of mortgage information:
  - Base Monthly Payment
  - Total Monthly Payment (with optional costs included)
  - Home Price
  - Down Payment
  - Loan Amount
  - Total of All Mortgage Payments
  - Total Interest Paid Over the Loan Term
- Highlighted key values for quick reference.

### Amortization Schedule:
- Displays a detailed **monthly breakdown**:
  - Period (Year-Month format, e.g., `2024-Jan`)
  - Interest Paid
  - Principal Paid
  - Remaining Balance
- Automatically calculates and displays for the entire loan term.

### Interactive Charts:
- **Amortization Chart** (Bar Chart):
  - Breakdown of Interest vs. Principal over time.
- **Monthly Costs Chart** (Pie Chart):
  - Visualizes the monthly costs, including optional inputs.

### PDF Export:
- Generate a **PDF summary** of:
  - Mortgage Summary Table
  - Amortization Chart
  - Monthly Costs Pie Chart (if applicable)
  - Amortization Schedule (Monthly)

### User-Friendly Design:
- Modern, responsive layout with **dark mode toggle** for enhanced readability.
- Fancy animations and smooth transitions for an engaging user experience.
- Intuitive input placeholders and error messages for better usability.

---

## Usage
1. Open the `index.html` file in any modern browser.
2. Enter the required fields:
   - Home Price
   - Down Payment (in dollars or percentage)
   - Amortization Period
   - Interest Rate
3. (Optional) Add costs like Property Tax, Condo Fees, and Other Costs.
4. Click **"Calculate Mortgage"** to view results.
5. Download the summary as a **PDF**.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/advanced-mortgage-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd advanced-mortgage-analysis
   ```
3. Open `index.html` in your browser to get started.

---

## Demo
Check out the live demo: [Live Demo Link](https://your-github-username.github.io/advanced-mortgage-analysis/)

---

## Technologies Used
- **HTML5**
- **CSS3** (with Bootstrap 5 for styling)
- **JavaScript**
  - Chart.js (for visualizations)
  - jsPDF + autoTable (for PDF generation)
- **Bootstrap 5** (for responsive design)
- **FontAwesome** (for icons)

---

## License
This project is open-source and available under the [MIT License](LICENSE).
