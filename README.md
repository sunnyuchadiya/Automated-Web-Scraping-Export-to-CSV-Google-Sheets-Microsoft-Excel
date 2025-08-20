 AutomatedWebScrapingExporttoCSVGoogleSheetsMicrosoftExcel
Automated web scraping pipeline that extracts data, converts it into CSV, emails it, and saves results to both Google Sheets and Microsoft Excel 365. Built with Google Cloud APIs and Microsoft Graph API, it’s ideal for market research, price tracking, and automated data workflows.

🚀 Overview
This project automates the process of web scraping, data extraction, and storage into multiple formats. It retrieves structured data from websites, generates a CSV file, emails it automatically, and saves the extracted information simultaneously to Google Sheets and Microsoft Excel (Office 365).

 ✨ Key Features
 🌐 Fetch HTML content from any website
 🧩 Parse and extract relevant information
 📊 Store results into a CSV file
 📧 Email the CSV as an attachment
 ☁️ Save results to Google Sheets
 💻 Save results to Microsoft Excel (Office 365)



 🛠️ How It Works
1. Fetch Website Content – Sends a request to the website and retrieves HTML data.  
2. Parse HTML – Extracts relevant information from the HTML structure.  
3. Store Data – Converts structured results into a CSV format.  
4. Send Email – Attaches the CSV file and delivers it to your configured email address.  
5. Save to Cloud – Stores extracted data into Google Sheets and Microsoft Excel for further analysis.  



 ⚙️ Setup Instructions
 1. Website Scraping
 Update the `"Fetch website content"` node with your target website URL.  

 2. Google Cloud Configuration
 Enable APIs for:
   Google Drive
   Google Sheets
   Gmail
 Add OAuth credentials to allow writeaccess and emailsending functionality.

 3. Microsoft Azure Configuration
 Configure Microsoft Graph API credentials.  
 Provide permissions for Excel and OneDrive access.

 4. Run the Workflow
 Execute the workflow to scrape, store, and share data automatically.



 📂 Use Cases
 🔎 Market Research
 📈 Price Tracking
 📰 News Aggregation
 🏢 Competitive Analysis
 🛍️ Ecommerce Product Monitoring



 📌 Requirements
 Node.js / Python (depending on your workflow implementation)  
 Microsoft Azure credentials with Graph API permissions  
 Google Cloud credentials with Sheets, Drive, and Gmail APIs enabled

thank you !!
