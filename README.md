# JSON Formatter and Syntax Highlighter

This is a lightweight, browser-based tool to format, parse, and highlight JSON data with syntax coloring. It is designed to handle raw JSON strings, escaped JSON, and evaluate and highlight nested JSON objects effectively.

## Features

- **Syntax Highlighting**:
  - Keys (`property`): Highlighted in **blue** (#204a87).
  - Strings (`string`): Highlighted in **green** (#4e9a06).
  - Numbers (`number`): Highlighted in **purple** (#ad7fa8).
  - Booleans and `null`: Highlighted in **gray italic** (#555753).
  - Braces (`{}`): Highlighted in **blue** (#729FCF).
  - Brackets (`[]`): Highlighted in **red** (#A40000).

- **JSON Beautification**:
  Automatically formats JSON for better readability with proper indentation.

- **Error Handling**:
  Displays `Invalid JSON` for improperly formatted JSON.

- **Supports Escaped JSON**:
  Automatically removes escape characters (like `\"`) for evaluation.

## Demo

You can view the demo by opening the `index.html` file in any modern browser.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/iamPrashanta/Json-Parser-Online.git
   cd Json-Parser-Online
