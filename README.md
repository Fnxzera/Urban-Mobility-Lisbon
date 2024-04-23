# Urban-Mobility-Lisbon
Overview
This project focuses on analyzing urban mobility data to gain insights into traffic restrictions and their impact on different locations. The dataset used in this project contains information about traffic restrictions due to various reasons such as filming, construction, and events, along with their impact, location, and duration.

# Project Goals
The main objectives of this project are:

Perform data preprocessing and cleaning to prepare the dataset for analysis.
Extract key insights from the data to understand patterns and trends in urban mobility.
Provide recommendations for improving traffic management based on the analysis results.
# Dataset
The dataset consists of the following columns:

  impact: Level of impact caused by the traffic restriction.
  restriction_circulation: Type of traffic restriction.
  morada: Location where the restriction is applied.
  motivo: Reason for the restriction (e.g., filming, construction).
  creation_date: Date and time when the restriction was created.
  Data_Inicio: Start date of the restriction.
  Data_Termino: End date of the restriction.
  Duração: Duration of the restriction.
# Operations Performed
  1. Data Preprocessing:
  Removed duplicates and missing values.
  Standardized date formats and converted timestamps to datetime objects.
  2. Data Analysis:
  Analyzed the frequency and duration of traffic restrictions.
  Explored temporal trends to identify patterns over time.
  Investigated the impact of restrictions on different locations and reasons.
  3. Visualization:
  Visualized key findings using plots and charts.
Created interactive maps to display the distribution of traffic restrictions.

# How to Use
To reproduce the analysis, follow these steps:

Clone the repository to your local machine.
Ensure you have the required dependencies installed (e.g., PySpark, Pandas).
Run the Jupyter Notebook file Urban_Mobility_Analysis.ipynb.
Follow the code cells to load the dataset and perform data preprocessing and analysis.
Explore the results and visualizations to gain insights into urban mobility patterns.
# Conclusion
This project demonstrates the process of analyzing urban mobility data using Python and PySpark. By preprocessing and analyzing the dataset, valuable insights were obtained regarding traffic restrictions and their impact on different locations. The findings can be used to inform decision-making processes and improve traffic management strategies in urban areas.

Feel free to customize the README according to your specific project details and results. This template provides a structured overview of the project, including its objectives, dataset description, operations performed, and instructions for reproducing the analysis.
