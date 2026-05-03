# -IT23682146-ITPM-ASS-01
#IT23682146 - ITPM Assignment 1
Option 1: Transliteration Accuracy Testing
This project tests the accuracy of the Chat Sinhala transliteration function available at:
https://www.pixelssuite.com/chat-translator
It evaluates how correctly the application converts chat-style Singlish input into Sinhala output using Playwright automation.

#Prerequisites

Python 3.11 or higher
Google Chrome (recommended)


#How to Install Dependencies
Open Command Prompt and navigate to the project folder:
cd /d C:\test_automation
Then run the following commands one by one:
pip install -U pip
pip install playwright openpyxl
playwright install

#How to Run Tests
Make sure the Excel file titled "Assignment 1 - Test cases.xlsx" is in the same folder as test_automation.py.
Then run the following command in Command Prompt:
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

#What Happens When You Run It

A browser window will open automatically
The script will type each Singlish input from the Excel file into the translator
It clicks the Transliterate button and waits for the output
The actual Sinhala output is recorded in the Actual output column
The Status column is automatically filled with Pass or Fail
Results are saved to the Excel file after every row


#Project Files
FileDescriptiontest_automation.pyMain Playwright automation scriptAssignment 1 - Test cases.xlsxExcel file containing all 50 test casesREADME.mdThis file

#Test Case Summary

Total test cases: 50
All test cases are negative (expected to Fail)
Covers all 24 Singlish input types as specified in Appendix 1
TC IDs follow the format: Neg_0001 to Neg_0050
Input length types: S (≤30 chars), M (31–299 chars), L (300–450 chars)


Registration Number
IT23682146
