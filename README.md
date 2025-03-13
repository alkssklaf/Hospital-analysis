# Hospital-analysis
## Project Overview
The primary purpose of this Power BI project is to analyze hospital data to provide valuable insights into operational capabilities and resource management. The intended audience for this Power BI project includes healthcare administrators.
## Features
The Power BI report consists of two pages. The first page presents basic metrics, while the second page provides in-depth metrics specifically for inpatient cases, where patients stay in the hospital. There are two cards visualisations which shows absolute and relative difference of patients in current and previous year:

![image](https://github.com/user-attachments/assets/0078c729-37f3-41dd-8d00-2b90c9d23a01)

The cards have green boarder when number is posititve. In case if number is negative, color is red. The numbers will help identify trend for this year in comparison with previous year.

Next is **pie chart** which shows relathionships between day case patients and inpatient. Slicer helps user filter chart by current year or all years:

![image](https://github.com/user-attachments/assets/6a54aed0-100d-4867-8436-0f177d381012)

Pie chart allowing administrators to assess changes over time and adjust resource allocation accordingly. The inpatient count is much lower than the day case count, it tells administrators that the hospital is doing more outpatient treatments, which might mean they are efficient but should check if they have enough resources for patients who need to stay overnight.

Most patients are concentrated in shorter time bands (0-3 months), it indicates efficient patient management.

<img width="313" alt="image" src="https://github.com/user-attachments/assets/fa2be75c-65bb-4748-9db0-7bc26b2daeeb" />


Line chart shows how number of patients has been changing through years. It helps to identify trend and may be useful in predictive analysis.

<img width="323" alt="image" src="https://github.com/user-attachments/assets/c44a3c2a-b3d0-4e86-a724-bb61f17012f5" />

## Installation Instructions
1.Download the Project Files:

Navigate to the GitHub repository where the project is hosted.
Click on the “Code” button and select “Download ZIP” to download all the project files, including the Power BI (.pbix) file and the data files.
Extract the downloaded ZIP file to a preferred directory on your local machine.

2.Open the Power BI File:

Double-click on the Power BI (.pbix) file to open it in Power BI Desktop.

3.Update the Data Source Path:

In Power BI Desktop, go to the “Transform Data” tab and select “Data Source Settings.”
In the Data Source Settings window, find the current path listed for your data files.
Select the data source and click “Change Source.”
Enter the absolute path to the directory where you stored your data files on your local machine.
Confirm the changes and click “Close.”

4.Refresh the Data:

Once the paths are updated, click on the “Refresh” button in Power BI Desktop to load the data from the new location.

5.Save Your Changes:

After confirming that the data is loading correctly, save your changes by clicking on “File” and then “Save.”
