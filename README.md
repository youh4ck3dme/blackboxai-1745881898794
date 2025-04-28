
Built by https://www.blackbox.ai

---

```markdown
# Bank Statement PDF Generator

## Project Overview

The Bank Statement PDF Generator is a simple Node.js application that generates a bank statement PDF by rendering an HTML template. It utilizes Puppeteer, a Node library that provides a high-level API to control headless Chrome. This project is tailored for generating statements from VÚB bank, displaying various transaction details in a structured format.

## Installation

To set up the project on your machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repo-url>
   cd <project-directory>
   ```

2. **Install dependencies**:
   Make sure you have Node.js installed, then run:
   ```bash
   npm install
   ```

## Usage

To generate a PDF from the bank statement HTML:

1. Ensure that the `updated_bank_statement.html` file is correctly formatted and ready for rendering.
2. Execute the following command in your terminal:
   ```bash
   node generate_pdf.js
   ```

This command will create a PDF file named `updated_bank_statement.pdf` in the same directory.

## Features

- Generates bank statement PDF from provided HTML.
- Supports headless Chrome for rendering, making it efficient for automated environments.
- Structured HTML layout to clearly present bank transactions.

## Dependencies

The project uses the following dependencies as defined in `package.json`:

- **puppeteer**: ^24.7.2

## Project Structure

The directory structure for this project is as follows:

```
/<project-directory>
├── generate_pdf.js           # Script to generate PDF using Puppeteer
├── package.json               # Node.js dependencies and project metadata
├── package-lock.json          # Exact versions of installed packages
└── updated_bank_statement.html # HTML template for the bank statement
```

### File Descriptions:

- **generate_pdf.js**: The main script that uses Puppeteer to convert the HTML to PDF.
- **updated_bank_statement.html**: The HTML file that contains the bank statement layout and transaction details.
- **package.json**: Lists project dependencies and scripts.
- **package-lock.json**: Provides a snapshot of the entire dependency tree.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute to the project or reach out for any questions or clarifications!
```