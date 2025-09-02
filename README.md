# CPWD eTender Data Extractor

**CPWD eTender Data Extractor** is a Python automation tool that extracts tender details from the **CPWD eTender portal**. The script scrapes the first 20 tenders and saves them into a **CSV file** for easy analysis.

---

## Features

- Automated navigation of CPWD eTender portal using **Selenium** 
- Handles alerts triggered by the **CPWD Signer** application 
- Extracts tender details including:
   - NIT/RFP Number
   - Name of Work
   - Estimated Cost
   - EMD Amount
   - Bid Submission Closing Date & Time
   - Bid Opening Date & Time
- Exports results to **tenders.csv** 

---

## Technologies Used

- **Python 3** – Core programming language
- **Selenium** – Automated browser interaction
- **Pandas** – Data handling and CSV export
- **Chromedriver** - WebDriver for Chrome browser
---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/cpwd-tender-scraper.git
   cd cpwd-tender-scraper
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
3. **Download Chromedriver:**  
   - Get the correct version from [here](https://chromedriver.chromium.org/downloads)  
   - Place `chromedriver.exe` in the project folder  

4. **(Optional) Install CPWD Signer:**  
   - Download from the CPWD eTender portal  
   - Run as **Administrator** for full functionality  

---

## Usage  

Run the script:  
```bash
python tender_scraper.py
```  

 **Output:**  
- Extracted data will be saved as:  
  ```
  tenders.csv
  ```  

---

##  Notes  

- Ensure `chromedriver.exe` is in the project folder  
- The CPWD portal may require **manual login or a digital certificate**  
- Script currently fetches the **first 20 tenders only**  

   
