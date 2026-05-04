# IT3040-Assignment1-IT23824256
# Test Automation Project

## Project Environment Setup

1. Install Python 3.11 or 3.12
2. Install Google Chrome (recommended) or let Playwright install Chromium automatically
3. Save the provided ZIP file to your D: drive
4. Extract the ZIP file to `D:\test_automation`
5. Open Command Prompt
6. Navigate to the extracted folder:cd /d D:\test_automation
7. Install dependencies (one-time):
    pip install -U pip
    pip install playwright openpyxl
    playwright install

## Running the Project

1. Ensure you are in the project directory:cd /d D:\test_automation
2. Run the Playwright script:
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Notes

- `--excel` specifies the path to the Excel file containing test cases
- `--url` specifies the target site for automation
- `--wait-ms` sets wait time before execution (milliseconds)
- `--type-delay-ms` sets typing delay between keystrokes
- `--slow-mo-ms` slows down execution for debugging
- `--save-every` saves results after each test case
- `--keep-open` keeps the browser open after execution
