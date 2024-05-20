
![images](https://github.com/code-red-Marshall/HR-Analytics/assets/82904501/2e65f27f-d18f-4c82-aa72-92eecd650c1c)



# HR Analytics Dashboard for ATLIQ Technologies
This repository contains the HR Analytics Dashboard project for ATLIQ Technologies. 
The dashboard was created to help the HR department and co-founders of ATLIQ Technologies to quickly gather insights from employee presence data over a period of 3 months.

## Project Overview
The main objective of this project was to reduce the time taken by the HR department to gather insights from employee presence data and to automate this process by creating a dynamic dashboard in Power BI.

## Stakeholders
The primary stakeholders for this project are the HR department and the co-founders of ATLIQ Technologies.

## HR Requirements
The dashboard was designed to provide answers to the following HR related queries:

- Working Preference between Work From Home (WFH) and Work From Office (WFO)
- Presence percentage by date
- Work from home percentage by date
- Sick leave percentage by date

## Data Gathering and Transformation
The data was gathered and transformed using the following steps:

- Load data and transform
- Duplicate the original data
- Remove all other columns but tables
- Unpivot tables except the first two columns
- Change the attribute column to date type and remove the errors
- Add a parameter named “worksheet”, keep the type as “text” and also change the name to the sheet name
- Create a function by right clicking on template and give a name as GetData
- Invoke the custom function under add column
- In GetData, delete irrelevant columns, rename and also change the data types.
- Close and apply.

DAX and Metrics
DAX (Data Analysis Expressions) was used to add additional columns to our data. The key takeaways from this step were:

- Group your measures under one place
- Use the Calculate function
- Add additional columns to our data using DAX

Dashboard Design

![Screenshot 2024-05-21 002130](https://github.com/code-red-Marshall/HR-Analytics/assets/82904501/d15f37e7-3157-4157-b49c-02c5c6bcea11)

The dashboard was designed with the aim of being a Minimum Viable Product (MVP). The key takeaways from this step were:

- Place your important insights in the dashboard
- A good insights report should enable the stakeholder to ask more “Why’s”?
- Copy Paste visuals and alter them to boost your productivity.

Future Enhancements
The following enhancements were not implemented as this is a free version of Power BI but these modifications are welcome:

- Sending alerts: If we upload the data in Power BI cloud, we can use this function
- Automatic Data Refresh: We use Sharepoint for this
- Setting Security levels for data

## Contributions
Contributions to this project are welcome. Please fork the repository and create a pull request with your changes.



