# SoIN_Housing_Analysis -  Code: You Data Analytics Capstone Project
Captstone project for Code: You exploring the relationships between housing availability, prices, and schools in Southern Indiana.


## Overview

 This project analyzes housing sales data from multiple resources (Redfin and Realtor.com Data Centers) along with the results of the ILEARN standardized test for school corporations in the Bartholomew, Clark, and Floyd counties located in Southern Indian. Hopefully, after view, analyzing, and visualizing the data I will have a better understanding of whether my family can afford to move to a house that's bigger than our current house that's located within a good school district in Souther Indiana, across the Ohio River from Louisville, KY.

## Data

The datasets used in this project containsinformation housing prices and standardized test scores. The housing data includes date of sales, median sale pricing during a specific time frame, price per square foot (median and connected with a specific sale). The standardized test scores are the subjects of Math, ELA (English Language Arts), Science, and Social Studies. 
- [2024 ILEARN Grade 3-8 Corporation Results (for Indiana) ](https://www.in.gov/doe/it/data-center-and-reports/)
- [Redfin Data Center](https://www.redfin.com/news/data-center/); File used in notebook can be downloaded from Kaggle [Kaggle](https://www.kaggle.com/datasets/rachelradwanski/real-estate-market-tracker-by-county)
- [National Center for Education Statistics](https://nces.ed.gov/ccd/districtsearch/index.asp?Search=1&details=1&InstName=&DistrictID=&Address=&City=&State=18&Zip=&Miles=&County=Clark&PhoneAreaCode=&Phone=&DistrictType=1&DistrictType=2&DistrictType=3&DistrictType=4&DistrictType=5&DistrictType=6&DistrictType=7&DistrictType=8&DistrictType=9&NumOfStudents=&NumOfStudentsRange=more&NumOfSchools=&NumOfSchoolsRange=more)

## Getting Started

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-project.git`to your IDE.
2. The County Market Dataset was too large to push to GitHub, please download it from Kaggle: [County Market Tracker](https://www.kaggle.com/datasets/rachelradwanski/real-estate-market-tracker-by-county)
3. Follow the instructions (below) to install and activate the virtual environment.
4. Then install the requirements.txt based on the instructions below. 
5. Open the HA_Cap_NB1.ipynb Notebook and explore the project.
6. Enjoy! 

###  Virtual Environment Instructions
---
1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
2. Create a virtual environment in the project folder. 
3. Activate the virtual environment.
4. Install the required packages. 
5. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |
### Project Structure
---

The project is organized as follows:

- **Data Exploration:** I utilized Jupyter notebooks to explore the dataset.

- **Analysis:** Used Python with the Pandas package to clean the data.

- **Visualizations :** Used Matplotlib to visualize my findings.


## Features Utilized for the project

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 2 CSV files found via realtor data centers and DOE in Indiana (the DOE file was split into 4 separate CSVs before reading into the Jupytper notebook.|
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. The calculated stats from various data points |
  | Make 3 matplotlib plots | Made various plots to show off my findings. |
  | Utilize a virtual environment      | Made a venv for this project. |
  | Create a Data Dictionary for your project | Created a Data Dictionary specific to this project. |
  | Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find clear notes describing each code block. |

## Dependencies

Python
Pandas
Jupyter Notebooks
Matplotlib

AI (ChatGPT and Chatbot Arena via LMSYS.org) was consulted for explanations on why certain parts of code worked and to troubleshoot errors.

