# Within-VR-Performance-Conditioned-on-Cognitive-Function
Within-VR Performance Conditioned on Cognitive Function

This repository contains the project materials for the INFO-B626 Human Factors Engineering for Health Informatics assignment. The project explores how cognitive function, assessed via Block Design scores, is associated with within-VR performance measured through a food preparation simulation. A novel quantitative metric—the Task Efficiency Score (TES)—is also proposed to provide additional insights into participant performance.
Learning Outcomes

Working on this project will allow you to:

  Develop Data Analysis Skills: Use Python (with pandas, scipy, scikit-learn, and matplotlib) in a Jupyter Notebook to process and analyze experimental data.

   Apply Statistical Methods: Compute descriptive statistics, perform Spearman correlation analyses, and fit a linear regression model to evaluate relationships between cognitive scores and task performance.

  Enhance Visualization Abilities: Create scatter plots with regression lines to illustrate key trends in the data.

  Design New Metrics: Develop and analyze the Task Efficiency Score (TES), which combines cognitive performance with task speed.

  Produce Reports in APA Format: Summarize the findings and statistical analyses in a report following APA guidelines.

   Integrate Multimedia Components: Combine code, Excel, CSV data, and PowerPoint slides (for project aims and background) into a cohesive research project.

Project Files

  Results.ipynb:
    Jupyter Notebook containing the full analysis workflow—from data loading and descriptive statistics to correlation analyses, linear regression, and visualization.

  Assessments.xlsx:
    Excel file containing participant IDs and Block Design scores for cognitive assessment.
    
Data Files

Due to file size limitations on GitHub, only one representative data file is provided in this repository. This sample file (named, C009_SimpleStew_MovementData.csv) is intended to illustrate the data structure and format used in the project. The full dataset, which contains all relevant records, is not included here. If you need access to the complete dataset, please refer to the contact information in the Contact section or follow the instructions provided in this README.

  Aim.pptx:
    PowerPoint presentation outlining the project’s goals, background, assignment details, and points breakdown.
    ​
  Report.doc:
    The final MS Word report summarizing the analysis, statistical findings, and interpretations in APA format.

Repository Setup and Usage
Cloning the Repository

To get started, clone the repository to your local machine by running:

git clone https://github.com/Hemanth-072/Within-VR-Performance-Conditioned-on-Cognitive-Function.git
cd Within-VR-Performance-Conditioned-on-Cognitive-Function

Installation and Dependencies

Make sure you have Python 3 installed. The project requires the following Python packages:

  pandas

   openpyxl

   scikit-learn

   scipy

   matplotlib

Install the dependencies using pip:

pip install pandas openpyxl scikit-learn scipy matplotlib

Running the Project

   Launch the Notebook:

   Open the Jupyter Notebook interface:

   jupyter notebook Results.ipynb

  Execute the Notebook:

  Run through each cell in the notebook to reproduce the analysis:

  Data Loading & Descriptive Statistics: Summarizes the Block Design scores.

  Total Recipe Completion Time: Reads session data from CSV files and calculates completion times.

   Correlation Analysis: Computes Spearman correlations between Block Design scores and completion times, and repeats using the Task Efficiency Score.

   Visualization: Generates scatter plots with a linear regression line to illustrate the relationships.

   Task Efficiency Score (TES): Calculates TES and examines its relationship with cognitive performance.

Report Generation:

   Use the generated outputs and visualizations to compile your final report (Report.doc) in APA format.

Project Overview and Analysis Details

  Descriptive Statistics:
    The notebook begins by calculating key summary statistics (mean, median, standard deviation, etc.) for the Block Design scores from Assessments.xlsx.

   Extracting Completion Times:
    The script searches for CSV files named with “CompletedStepsData” and extracts the maximum session time (or an alternative “Times” column) for each participant, aggregating these into a DataFrame.

  Correlation Analysis:

  Spearman Correlation (Block Design vs. Completion Time):
        Merges the cognitive and performance data by participant IDs and calculates a Spearman correlation coefficient (with p-value) for the relationship.

  Spearman Correlation (TES vs. Block Design):
        After computing TES, a second correlation is performed to assess its relationship with the cognitive scores.

  Scatter Plots and Linear Regression:
    The project visualizes the relationships with:

   Scatter plots to display the raw data.

  A linear regression model (using scikit-learn) to fit and overlay a trend line, illustrating the predictive relationship.

   Task Efficiency Score (TES):
    Calculated using the formula:
    TES=(Block Design ScoreTotal Completion Time)×100
    TES=(Total Completion TimeBlock Design Score​)×100

 This provides an efficiency measure that integrates cognitive capability with performance speed.

Contributing and Further Development

This repository lays the groundwork for advanced analysis. Potential next steps include:

  Expanding the model to incorporate additional variables and using more sophisticated machine learning techniques.

  Implementing cross-validation and performance metrics for the regression models.

   Enhancing visualizations with interactive dashboards or more detailed plots.

Feel free to fork this repository, experiment with the code, and propose improvements via pull requests.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Contact

For questions or further discussion about this project, please reach out to:

  Project Maintainer: [Hemanth Sai Kumar Gaddam]

   Email: [hemanthsaikumar07gaddam@gmail.com]

  GitHub: Hemanth-072
