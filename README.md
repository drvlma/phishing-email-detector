# Phishing Email Detection Dashboard

This is a lightweight phishing email logging and detection tool built in Google Sheets with automated flagging using Google Apps Script.

## Features
- Logs suspicious emails
- Auto-flags phishing indicators (e.g., suspicious links, urgent language, sender mismatch)
- Uses conditional formatting for easy visualization
- Requires no installation — 100% Google Sheets-based

## Technologies Used
- Google Sheets
- Google Apps Script (JavaScript-based)


## 🔗 Spreadsheet Template
You can view or make a copy of the phishing detection tool here:  
[📄 Phishing Email Detection Template (Google Sheets)](https://docs.google.com/spreadsheets/d/1zBzChBL2E2nEjq2wexjqHc0aw8tOTK2mTB5G_b7rCjc/edit?usp=sharing)

## 🛠️ How to Use

1. **Make a Copy**  
   Open the template and go to `File → Make a copy` to save it to your own Google Drive.

2. **Open Script Editor**  
   In your copied version, click `Extensions → Apps Script`.

3. **Paste the Script Code**  
   Replace any default code with the code from `phishing_detector.gs` in this repo.

4. **Save and Close the Editor**  
   Click the floppy disk icon 💾 or `File → Save`, then close the script editor.

5. **Start Logging Emails**  
   Enter sample email data in each row. The sheet will auto-flag emails with:
   - Suspicious links
   - Urgent or alarming language
   - Sender name mismatch

6. **View Flagged Emails**  
   The “Flagged as Phishing?” column will automatically update to **"Yes"** if any red flags are detected.

## Disclaimer
This tool is for educational and awareness purposes only. It does not provide comprehensive email security or filtering.
