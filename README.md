# Ice Cream Ratings Analysis sxcs

## Overview

This Python script analyzes ice cream ratings data stored in a CSV file using the pandas library. It explores various visualization techniques to understand and interpret the ratings given to different flavors of ice cream.

## Requirements

- Python 3.x
- pandas library
- numpy library
- matplotlib library

## Usage

1. Ensure you have Python installed on your system.
2. Install the required libraries by running `pip install pandas numpy matplotlib` in your terminal or command prompt.
3. Download the 'Ice Cream Ratings.csv' file and place it in the same directory as the Python script.
4. Run the script 'ice_cream_ratings_analysis.py'.

## Description

- **Reading Data:** The script reads the ice cream ratings data from the CSV file using pandas, with the 'Date' column set as the index.

<img width="561" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/fb788c72-f975-4d63-96d9-4bea336dd8e6">

- **Exploratory Data Analysis and Visualization:**

    - **Line Plots:** The script generates line plots to visualize the ice cream ratings over time.

<img width="545" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/990c9c85-9819-40fd-9961-9e95f31f7cf9">

    - **Subplots:** Multiple line plots are created as subplots to compare different aspects of the ratings.
<img width="545" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/739c561a-8c98-45a9-859d-01244fde4787">

    - **Bar Plots:** Bar plots are used to visualize the ratings of different flavors of ice cream. Stacked and horizontal bar plots are also demonstrated.

 <img width="413" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/5557919d-8c81-4f04-aa00-b0de737d9dab">
 <img width="497" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/89b9cd87-d5a5-4e77-ab44-d88eb8bf65e3">
 <img width="489" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/df844e36-c3f9-40b7-b485-2a9ddd191e69">
 <img width="490" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/11105df5-954e-4950-bcfd-d62ac1f176f0">

    - **Scatter Plot:** A scatter plot is created to visualize the relationship between texture and overall ratings.
<img width="500" alt="image" src="https://github.com/Raezoxc/Data_Visualization_Python/assets/153198226/9b218628-322b-415f-9349-3aa6394a4e3b">

    - **Histogram:** The distribution of ratings is visualized using a histogram.

    ![Histogram](/screenshots/histogram.png)

    - **Box Plot:** A box plot is generated to show the distribution of ratings and identify any outliers.

    ![Box Plot](/screenshots/box_plot.png)

    - **Area Plot:** An area plot is created to visualize the cumulative sum of ratings over time.

    ![Area Plot](/screenshots/area_plot.png)

    - **Pie Chart:** A pie chart is generated to represent the distribution of ratings for different flavors of ice cream.

    ![Pie Chart](/screenshots/pie_chart.png)

## Output

The script produces various visualizations to analyze the ice cream ratings data and gain insights into the quality and popularity of different flavors.

## Author

[Your Name]

## License

This project is licensed under the [MIT License](LICENSE).
