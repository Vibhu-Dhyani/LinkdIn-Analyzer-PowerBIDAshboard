
# LinkedIn Analyzer (End-to-End Project)

This project depicts end-to-end scenario of data collection > cleansing > visualization.




## RoadMap

- Data Collection :
    - Exctract the Personal Info data provided by linkdin in form of csv files.
    - Creation of a linkdIn web-scrapper using Selenium and BeautifulSoup in python. 

- Data Cleansing :
    - Cleaned the data using pandas.

- Data Storing : 
    - Stored the pandas data frame with scrapped data to a local SQL server.

- Power BI : 
    - Creation of Power BI Dashboard to visualize the collected data.


## Features of Power BI Dashboard

### This power bi dashboard has two pages :
- Personal Info : created using data that linkding provides for every user e.g  applications, messages, companies applied, connections made, etc.
- Jobs Details : created using scrapped data from linkdin using selenium and beautifulsoup.

### Personal Info :

- This page contains KPI cards to view the connections, companies, invite sent, invite received, endorsements.
- An Area Chart to visualize number of connections by Date.
- Distribution of connections over companies.
- Distribution of skills over endorsements.
- Applied Jobs by company names and roles.
- A decompasition tree to view connections by company names and postions.
- A Filter pannel to filter the info for selected date, comapny, position, skills.

### Job Details : 
#### Pre-processing
- This Page is having the scrapped data which was collected using a python script.
- Python script utilized Selenium and BeautifulSoup to atomate and parse the html respectively.
- Post that data is being stored into pandas dataframe and cleansed using the same.
- After that it being pushed to a local SQL Server.

#### Power BI
- Data is pulled into the power bi from local SQL Database.
- Map visual to visualize the location of the jobs.
- HTML content to parse the html of job description.
- Table to view other details s.a company name, employement type,  seniority level, etc.
- Also Job title contains the WEB URL of the job post in LinkIn.
- A Filter pannel to filter on comapny, relative time, employement type, location.

### Additional features :
- It comes with two modes -> Dark and Light modes.
- A hidden filter pannel which can be pulled when needed.
- Comes with advance UI/UX design.



## Screenshots

![Personal Info - Light Mode](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/image%201.png)

![Personal Info - Light Mode - Filter Pannel](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/Slide%2016_9%20-%202.png)


![Personal Info - Dark Mode](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/Slide%2016_9%20-%205.png)


![Job Details - Light Mode](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/Slide%2016_9%20-%203.png)


![Job Details - Light Mode - Filter Pannel](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/Slide%2016_9%20-%204.png)

![Job Details - Dark Mode](https://github.com/Vibhu-Dhyani/LinkdIn-Analyzer-PowerBIDAshboard/blob/master/linkdIn_analyzer/DashboardImages/Slide%2016_9%20-%206.png)


## 🚀 About Me
I'm a data analyst, full stack developer, ML/DL developer...


## Authors

- [@Vibhu-Dhyani](https://github.com/Vibhu-Dhyani/)

