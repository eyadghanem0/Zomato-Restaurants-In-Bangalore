# **Zomato Restaurants In Bangalore, India**

## **About the Project**
- This project is a professional analysis report of a licensd Kaggle dataset, it was designed by Eyad Ghanem(GitHub username is eyadghanem0).
In addition to the README file, the python notebook, the Power BI file and the PDF version are included in the project's repoistory. The Power BI file(.pbix) is recommended to experience
the full features of the report (tooltips,filters,view edits....).
You can freely access the dataset through the following URL: https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants
- Zomato is one of the leading platforms for restaurants reviews and food ordering. Bangalore, with its rich and diverse food culture, is
an ideal city for such analysis; it has over 12,000 restaurants offering food from all over the world. The results and insights of this report can help anyone planning to visit Bangalore,
planning to improve or open a restaurant or just a local trying to enjoy the city's unlimited possibilties, by gatehering information about customer prefrences, pricing and cuisine trends.

## **Data Preparing**
- First, python was used to prepare the dataset.The "approximate price for two" column was converted from Indian Rupees to USD. The "rate" column was converted to numeric format represnting
the restaurant's rate out of 5. Missing and empty values were cleaned for accurate results.
- Also, only one row per restaurant was kept in the first dataframe because most of them appeared multiple times with identical values in the columns required
to complete the report. Then, two other dataframes were created, each with either the "rest_type" or "cuisines" column expaded. These columns had rows with multiple values (restaurants
that offer more than one cuisine and belong to more than a single type) . All three dataframe, so splitting was crucial to visualize the correct count of each category. Finally, all 
three dataframe were saved as csv files.

## **Power BI Report**
The saved csv files were imported into Power BI. New columns, a new table, and mesaures were also added to improve and finalize the visualizations. The report is divided into pages
titled according to their content.

## You can open the python lab(.ipynb) to view the code, the Power BI file to view the report or just the pdf file for a quick view.

