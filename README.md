# CMU Server Logs Project
This project analyzes the Virtual Desktop Infrastructure (VDI) machine usage logs of 3000+ users at Central Michigan University using R, uncovering academic usage trends, seasonal fluctuations and identifying data issues. It also conducts data wrangling and filtering on the dataset, which is a huge one with 3.1 million initial observations before analyzing the data to support infrastructure improvements as well as provide recommendations. 

The entire project was conducted in **R Studio**, including:
- Data import and cleaning
- Transformation and reshaping
- Exploratory data analysis (EDA)
- Visualization
- A presentation video tailored towards a non-technical audience

# Data Source
The original dataset is hosted externally in this link below:
https://www.kaggle.com/datasets/munemshariarshams/vdi-server-logs-cmu

## Project Workflow

The analysis follows a structured data analytics workflow:

1. **Data Acquisition**
   - VDI server log dataset collected from Central Michigan University systems.
   - Dataset originally contained over **3.1 million observations**.

2. **Data Cleaning**
   - Removal of incomplete and invalid records
   - Standardization of timestamps and usage fields
   - Filtering corrupted log entries

3. **Data Transformation**
   - Reshaping the dataset for analysis
   - Creating derived variables related to session duration and usage patterns

4. **Exploratory Data Analysis (EDA)**
   - Identifying peak server usage times
   - Detecting seasonal patterns during academic semesters
   - Exploring user activity distribution

5. **Visualization**
   - Time-series visualizations of server usage
   - Usage distribution plots
   - Comparative activity charts

6. **Insights & Recommendations**
   - Identification of infrastructure bottlenecks
   - Recommendations for server scaling and load balancing
   - Suggestions for improving system availability during peak usage periods

# Video Presentation
The video presentation is hosted in this link below:
https://cmich.webex.com/cmich/ldr.php?RCID=24104455395fd20fd40ece266af89d45

## Files Included

| File / Folder | Description |
|----------------|-------------|
| `final_project_file.Rmd` | Main R Markdown notebook containing the full analysis workflow including data cleaning, transformation, exploratory analysis, and visualizations. |
| `final_project.html` | Rendered HTML output of the R Markdown file showing the full analysis and results. |
| `final knitted output.docx` | Word document version of the knitted R Markdown report. |
| `Presentation Slide_Sharms.pptx` | Project presentation slides summarizing the analysis, findings, and recommendations. |
| `My Analysis and Findings.pdf` | Detailed written report explaining the results, insights, and infrastructure recommendations. |
| `Visuals/` | Folder containing all generated visualizations and charts used in the analysis and presentation. |
| `README.md` | Project documentation describing the objective, dataset, methods, and results of the project. |

# Libraries used in R:
tidytext,
ggplot2,
dplyr,
tidyr,
ggraph,
igraph,
