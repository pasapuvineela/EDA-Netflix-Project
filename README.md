Netflix Movies & TV Shows - Exploratory Data Analysis (EDA)

Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Netflix Movies & TV Shows Dataset** using Python. The goal is to understand the dataset, clean the data, analyze patterns and trends, create visualizations, and provide business insights based on the findings.

Objective
The main objectives of this project are to:
* Load and inspect the dataset.
* Clean missing and duplicate data.
* Perform exploratory data analysis (EDA).
* Create meaningful visualizations.
* Generate business insights and recommendations.

 Dataset
**Dataset:** Netflix Movies & TV Shows Dataset
The dataset contains information about Netflix content, including:
* Show ID
* Type (Movie/TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

## Tools and Technologies
* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

Data Cleaning
The following preprocessing steps were performed:
* Removed duplicate records.
* Handled missing values.
* Filled missing values in Country, Director, and Cast columns.
* Converted the `date_added` column into datetime format.
* Verified data types and dataset quality.

Exploratory Data Analysis
The following questions were analyzed:
1. Movies vs TV Shows distribution.
2. Top countries producing Netflix content.
3. Most common content ratings.
4. Content released over the years.
5. Top directors with the highest number of titles.

 Data Visualizations
The project includes the following visualizations:
* Bar Chart
* Line Chart
* Histogram
* Scatter Plot
* Pie Chart
* Heatmap

Key Insights
* Netflix contains more Movies than TV Shows.
* The United States contributes the highest number of Netflix titles.
* Content production increased significantly after 2015.
* TV-MA is one of the most common content ratings.
* Missing values were mainly found in the Director and Cast columns before cleaning.

 Business Recommendations
* Increase investment in popular content categories.
* Expand content production in underrepresented countries.
* Improve metadata quality by reducing missing information.
* Continue releasing fresh content regularly.
* Use audience preferences to guide future content strategy.

 Project Structure
EDA-Netflix-Project/
│── EDA_Project.ipynb
│── netflix_titles.csv
│── README.md

Conclusion
This project demonstrates the complete EDA process, from data loading and cleaning to visualization and insight generation. The analysis provides valuable information about Netflix's content distribution, growth trends, and potential business opportunities.


