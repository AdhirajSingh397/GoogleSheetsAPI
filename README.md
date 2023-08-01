# GoogleSheetsAPI
developed an API (using google script) that retrieves data from Google Sheets and displays it on a website. To achieve this, we employ a Google Script that scrapes data from the MLH website and stores it in Google Sheets. The collected data is then utilized by our API to present it on the website. Inspired from MLH hackathon, event hosted by Wei.


## How it Works

The API follows a simple workflow to ensure smooth integration and data presentation:

1. **Google Sheets Setup**: Create a new Google Sheet and access the "Extensions" menu to find "App Script."

2. **Project Configuration**: Within the App Script, rename the project as needed. Create a new file dedicated to scraping data from the MLH website, handling the data extraction process.

3. **Endpoint Setup**: Create another file in the App Script editor that sets up the API endpoint, allowing communication between your website and Google Sheets.

4. **Website Integration**: Use the provided HTML and JavaScript project from the "simple-website" repository to display data on your website. Customize the code to match your website's design and integrate the API to fetch and display data.
