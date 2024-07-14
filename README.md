# Google Ads Quality Score Tracker

This Google Apps Script automates the retrieval and tracking of Quality Scores for keywords in Google Ads, storing the data in a Google Sheets document.

## Features

- **Automated Data Retrieval:** Fetches keywords and their Quality Scores from Google Ads.
- **Data Logging:** Captures Date, Campaign, Ad Group, Keyword, and Quality Score.
- **Error Handling:** Logs errors for monitoring.
- **Google Sheets Integration:** Writes the data to a specified Google Sheets document.

## Setup

1. **Open Google Sheets:**
   - Create a new Google Sheets document or use an existing one.
   - Note the spreadsheet ID from the URL. It’s the part between `/d/` and `/edit`.

2. **Open Google Apps Script Editor:**
   - In Google Sheets, go to `Extensions` > `Apps Script`.

3. **Copy the Script:**
   - Replace the content with the following script:

4. Replace Spreadsheet ID:

Replace 'YOUR_SPREADSHEET_ID' with the ID of your Google Sheets document.

5. Authorize Script:

Save the script and run the main function.
Authorize the script to access your Google Ads and Google Sheets data when prompted.

6. Verify Data:

Check your Google Sheets document (Sheet1 or your specified sheet name) to ensure the script has populated the data correctly with Date, Campaign, Ad Group, Keyword, and Quality Score.

7. Usage
Manual Execution: Run the script manually from the Google Apps Script editor.
Scheduled Execution: Set up a trigger in Google Apps Script to run the script at regular intervals (e.g., daily, weekly).
