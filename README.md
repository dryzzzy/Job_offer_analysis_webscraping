# 
**Project Goal and Description**

The goal of the project is to acquire, store, and interpret data on job offers published on the website nofluffjobs.com. The job positions being analyzed are:
- Data Analyst
- Data Engineer
- Data Scientist

The project addresses the following questions:
- What is the estimated cost of hiring such individuals?
- What are the salary ranges proposed in each offer?
- In which cities can such individuals be hired?
- Is it possible for a team consisting of these three types of employees to be established in one city?

To solve this task, I am using the following tools and libraries:
- Selenium: to gather information on currently existing job offers,
- BeautifulSoup: to process unstructured data (HTML code) into structured data (DataSet),
- Pandas: to perform data transformations,
- Matplotlib: to present the results.

What each file consists of?
The code is stored in 4 files in 'notebooks'. Each of the 4 files solves a different step of the project, from data collection to final analysis.
'Drivers' consists of the latest chromedriver.exe (version 127.0.6533.88 - download link -> https://storage.googleapis.com/chrome-for-testing-public/127.0.6533.88/win64/chromedriver-win64.zip). In case of obsolence go to this site https://googlechromelabs.github.io/chrome-for-testing/ and download the appropriate chromedriver version for your browser.
'Data' contains files processed when running subsequent notebooks with code.
