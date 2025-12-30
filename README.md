# Kidum LMS Reporter

A secure, web-based tool to generate student attendance and work group reports from the Kidum LMS. This application automates the process of fetching data, filtering by the current week, and exporting formatted Excel files.

**Built with:** [Streamlit](https://streamlit.io/) & [Pandas](https://pandas.pydata.org/)

## Features

* **Secure Login:** Authenticates directly with the Kidum LMS API using secure tokens.
* **Weekly Filtering:** Automatically calculates the current week (Sunday–Saturday) to filter relevant data.
* **Multiple Report Types:**
    * **Full Report:** Raw export of all data.
    * **Weekly Report:** All student activity for the current week.
    * **Group Specific:** Filter data for a single group within the current week.
    * **Summary Report:** Counts unique students per Group and Hour (handling duplicate entries).
* **Excel Export:** One-click download of `.xlsx` files ready for administrative use.

---

##  How to Use (Web App)

1.  Open the App link: **[Insert Your Streamlit App Link Here]**
    *(e.g., https://kidum-reports.streamlit.app)*
2.  **Login:**
    * If configured, click **" Auto-Login"** to use stored credentials.
    * Otherwise, manually enter your Kidum Admin email and password.
3.  **Select Report:** Choose the type of report you need from the radio buttons.
4.  **Download:** Preview the data on screen and click **" Download Excel"** to save it to your computer.

---

## 🛠️ Local Development & Setup

If you want to run this code on your own computer or modify it, follow these steps.

### 1. Prerequisites
* Python 3.10 or higher
* pip (Python package manager)

### 2. Installation
Clone the repository and install the required libraries:

```bash
git clone [https://github.com/your-username/kidum-reports.git](https://github.com/your-username/kidum-reports.git)
cd kidum-reports
pip install -r requirements.txt
