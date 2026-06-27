**📧 Gmail Excel Attachment Automation using Google Apps Script & Power Query**

 Automating the extraction, transformation, and consolidation of Excel attachments received via Gmail into    a single master dataset using Google Apps Script and Microsoft Power Query.

**📌 Table of Contents**
 
[Overview](#-overview)

[Business Problem](#business-problem)

[Project Objective](#project-objective)

[Dataset](#dataset)

[Tools & Technologies](#tools--technologies)

[Project Structure](#project-structure)

[Workflow](#workflow)

[Data Processing](#data-processing)

[Key Features](#key-features)

[Dashboard / Output](#dashboard--output)

[How to Run This Project](#how-to-run-this-project)

[Results & Business Impact](#results--business-impact)

[Future Improvements](#future-improvements)

[Author](#author)

**📖 Overview**

This project automates the process of collecting Excel attachments from Gmail and consolidating them into a single master dataset using Google Apps Script and Microsoft Power Query.

Instead of manually downloading and combining multiple Excel files, the entire workflow is automated, making business reporting faster, more accurate, and highly efficient.

**💼 Business Problem**

Many organizations receive multiple Excel reports every day through Gmail.
The manual process involves:

* **Downloading every attachment**

* **Opening each Excel file**

* **Copying and combining data**

* **Creating a master report**

  This process is repetitive, time-consuming, and prone to human errors.

**🎯 Project Objective**

The objective of this project is to automate the collection and consolidation of Excel attachments received through Gmail into a single master dataset.

The solution reduces manual effort, improves data accuracy, saves reporting time, and enables faster business decision-making.

**📂 Dataset**

The project processes Excel attachments received via Gmail.

  **Sample Files**

* **MUMBAI.xlsx**

* **CHENNAI.xlsx**

* **DELHI.xlsx**

* **NAGPUR.xlsx**

After processing, all files are appended into a single Master Dataset for reporting and analysis.

**🛠️ Tools & Technologies**

* Microsoft Excel

* Power Query (M Language)

* **Google Apps Script

* Gmail API (via Web App)

* Git & GitHub

**📁 Project Structure**

```text

gmail-power-query-excel-automation/
|
|-README.md
|-Project_Report_Gmail_Power_Query_Excel_Automation
|
|-Sample-data/
| |-MUMBAI.xlsx
| |-CHENNAI.xlsx
| |-DELHI.xlsx
| |-NAGPUR.xlsx
|
|-output/
| |-Combine data
|
|-scripts/
| |-scripts code
|
     
```

**🔄 Data Processing**

The project automatically performs:

* Gmail attachment extraction

* API generation

* Power Query data import

* Base64 to Binary conversion

* Excel file loading

* Data transformation
  
* Automatic append of multiple Excel files
  
* Master dataset creation
  
**✨ Key Features**
  
* Fully automated Gmail attachment extraction
  
* No manual downloading of Excel files
  
* Automatic data consolidation

* Dynamic Power Query refresh

* Handles multiple Excel attachments

* Reduces manual reporting effort

* Improves data accuracy

* Scalable automation workflow

 **📊 Output**

 The final output consists of:

* Master Excel Dataset

* Combined Data Table

* Ready-to-use Reporting Dataset

* Business-ready data for Excel
  
**🚀 How to Run This Project**

1.Enable IMAP in Gmail.

2.Deploy the Google Apps Script as a Web App.

3.Copy the generated Web App URL.

4.Open Excel.

5.Go to Data → Get Data → From Web.

6.Paste the Web App URL.

7.Refresh Power Query.

8.The latest Gmail Excel attachments will be automatically consolidated.

**📈 Results & Business Impact**

* Eliminated manual downloading of Excel attachments

* Automated repetitive reporting tasks

* Reduced reporting time significantly

* Improved data consistency and accuracy

* Increased productivity of business teams

* Enabled faster decision-making with up-to-date data

**🔮 Future Improvements**

* Power BI integration

* SQL Database storage

* Automatic scheduled refresh

* Cloud deployment

* Email notifications after processing

* Error logging and monitoring

* Duplicate attachment detection

**👨‍💻 Author**

Swastik Kumar

B.E. Computer Engineering

Data Analyst | Excel | SQL | Power BI | Python | Google Apps Script

GitHub: https://github.com/SwastikAnalytics


