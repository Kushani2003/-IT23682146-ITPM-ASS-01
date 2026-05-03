# IT23682146 - ITPM Assignment 1
## Option 1: Transliteration Accuracy Testing

This project tests the accuracy of the Chat Sinhala transliteration function available at:
https://www.pixelssuite.com/chat-translator

## Prerequisites
- Python 3.11 or higher
- Google Chrome (recommended)

## How to Install Dependencies

Open Command Prompt and navigate to the project folder:

    cd /d C:\test_automation

Then run:

    pip install -U pip
    pip install playwright openpyxl
    playwright install

## How to Run Tests

    python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Project Files
- test_automation.py - Main Playwright automation script
- Assignment 1 - Test cases.xlsx - Excel file with 50 test cases
- README.md - This file

## Test Case Summary
- Total: 50 negative test cases (all expected to Fail)
- Covers all 24 Singlish input types
- TC IDs: Neg_0001 to Neg_0050

## Registration Number
IT23682146
