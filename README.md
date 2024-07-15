# Python

Python Data Analysis and Visualization Projects

Welcome to the Python Data Analysis and Visualization Projects repository! This repository is a collection of diverse projects showcasing the use of Python for data analysis and visualization. Whether you are a beginner looking to learn data science or an experienced professional seeking advanced techniques, this repository has something for everyone.

Current Projects

1. Most Streamed Spotify Songs 2024

This project analyzes the "Most Streamed Spotify Songs 2024" dataset. Key objectives include:

Data Cleaning and Preparation: Handling missing values and converting data types.

Exploratory Data Analysis (EDA): Generating summary statistics and visualizing data distributions.

Trend Analysis: Identifying trends in release dates and popularity metrics.

Visualization: Creating scatter plots, histograms, and bar charts with trend lines.

Advanced Analysis: Calculating Interquartile Range (IQR) and implementing conditional counts.

Example code snippets and detailed explanations are provided to guide you through the analysis process.

2. Data Anomaly Checker

This project focuses on the "Data Anomaly Checker," a desktop application designed to identify and report invalid data entries within a dataset. Key objectives include:

File Upload and Loading: Allowing users to upload a CSV file using a file dialog. The file is read into a pandas DataFrame, and the filename and loaded data are displayed.

Data Anomaly Detection: Customized functions detect anomalies in specific columns, including non-text values, entries exceeding specified lengths, and empty or null values.

Updating the User Interface: Text boxes in the UI are updated with the indices of rows containing anomalies. Each type of anomaly has its dedicated text box, and a header value is displayed.

Color Coding and Warnings: Text boxes with anomalies are highlighted in light red. A warning message emphasizes the importance of non-empty cells in specific columns.

User Interface Design: The app uses various Tkinter widgets to create a user-friendly interface, including labels, text boxes, buttons, and frames to organize the layout and functionality. Custom messages from the developer are also displayed.

The application ensures efficient identification and addressing of data anomalies in user datasets.

3. Travel Data Analysis Project

This project focuses on analyzing travel data over multiple years, with an emphasis on quarterly breakdowns. Key objectives and features of the project include:

Data Preparation:

Date Handling:

Converting travel dates to quarterly periods using pandas.
Filtering data by specific quarters.

Data Aggregation:

Quarterly Counts:

Calculating the number of entries (trips) per quarter from 2020 to 2023.
Storing these counts in a dictionary for easy access and plotting.

Quarterly Average Costs:

Computing the average cost of travel for each quarter.
Normalizing costs to enhance interpretability (e.g., dividing by 1000).

Visualization:

Bar and Line Plots:

Creating bar plots to visualize the number of entries per quarter.
Plotting average travel costs per quarter using line plots for trend analysis.
Customizing plot titles, labels, and layouts for clarity.

Heat Map Generation:

Heat Map:

Preparing a pivot table to organize data by quarter and metric (e.g., counts or costs).
Utilizing seaborn to generate a heat map for a visual representation of data distribution and trends.

Future Projects

This repository is a work in progress, and new projects will be added regularly.
