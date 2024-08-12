# Marketing Analytics Project

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![Microsoft PowerPoint](https://img.shields.io/badge/Microsoft_PowerPoint-B7472A?style=for-the-badge&logo=microsoft-powerpoint&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Project Overview
This project is a comprehensive data analysis and machine learning exercise focused on consumer behaviour and marketing strategy optimisation. The objective is to evaluate the impact of targeted marketing strategies on different segments of the supermarket’s consumer base, using predictive modeling and data visualisation techniques.

## Project Structure

    ├── LICENSE
    ├── README.md            <- README.
    ├── Source
    │   │
    │   ├── a1_Dataset_10Percent                   <- 10% Samples for machine learning.
    │   ├── a2_Dataset_90Percent                   <- Remaining part of the samples for testing the model.
    │ 
    ├── Codes                <- Code of the modelling.
    │   │
    │   ├── b1_Marketing_Campaign.ipynb            <- Machine learning modelling.
    │   └── b2_Predictor_Marketing.ipynb           <- Predictions based on modelling.
    │ 
    └── Reports              <- Folder containing the final reports/results of this project.
         │
         ├── Background                            <- Dashboard Backgrounds.
         ├── Dashboard                             <- Dashboard Previews in PNG.
         │    ├── Dashboard_1_Modelling & Analysis.png
         │    └── Dashboard_2_Demographics.png
         └── Marketing Project.twb                 <- Final Dashboard.

### Problem Description
ABC Supermarket, with a loyalty program encompassing approximately 225,000 members, is planning to launch a new range of organic products. As part of their marketing strategy, they initially distributed sample kits to 10% of their loyalty program members to gauge interest and purchasing behaviour. The challenge now is to analyse the data from this initial group to determine the optimal number of sample kits to distribute to the remaining 90% of the members in order to maximise the effectiveness of the marketing campaign.

### Dataset Information

The dataset contains 22,500 samples, segmented into an 80% training set and a 20% testing set. The dataset used for this project contains comprehensive information about consumer demographics, purchase behaviours, and marketing response indicators. The key attributes of the dataset include:

- **ID (PRIMARY KEY):** Customer Loyalty Identification No.
- **DemAffl:** Affluence Grade on a Scale of 1 to 30.
- **DemAge:** Age, in years.
- **DemClusterGroup:** Neighborhood group.
- **DemGender:** Male (M)/ Female (F)/ Unknown (U).
- **DemReg:** Geographic region.
- **DemTVReg:** Television region.
- **LoyalClass:** Loyalty status: Tin, Silver, Gold, Platinum.
- **LoyalSpend:** Total amount spent.
- **LoyalTime:** Time as loyalty card member.
- **TargetBuy:** Purchased or not, 1=Yes & 0=No.

### Project Workflow
**1. Data Collection:**
- **Steps:** Use a dataset of 22,500 data points was used, representing 10% of the total target population (225,000 consumers). Import data from the `a1_Dataset_10Percent.xlsx` into Jupyter Notebook. 
- **Tools:** Microsoft Excel, Jupyter Notebook.

**2. Data Preprocessing:**
- **Steps:**
  - **Data Cleaning:** Use Python libraries such as pandas to handle missing values, correct inconsistencies, and remove duplicates from the dataset.
  - **Data Transformation:** Perform necessary transformations, including converting data types and creating new features (e.g., encoding categorical variables, calculating relevant metrics).
  - **Normalisation:** Standardise numerical values using techniques such as scaling to ensure consistency across the dataset.
- **Tools:** Python, Jupyter Notebook, pandas, NumPy.

**3. Exploratory Data Analysis (EDA):**
- **Steps:**
  - **Summarisation:** Use descriptive statistics to gain initial insights and understand data distributions and relationships among key variables.
  - **Correlation Analysis:** Investigate correlations between variables to identify potential predictors for marketing strategy effectiveness.
- **Tools:** Python, Jupyter Notebook, Pandas, NumPy.

**4. Data Analysis:**
- **Steps:**
  - **Predictive Modeling:** Use machine learning models to predict customer behaviour and the likelihood of purchase based on the sample data.
  - **KPI Calculation:** Compute metrics such as the percentage of willing buyers among selected consumers, the percentage of total willing buyers reached, and the percentage of non-buyers successfully avoided.
  - **Model Evaluation:** Assess the performance of the models using metrics like accuracy and the confusion matrix.
- **Tools:** Python, Jupyter Notebook, Scikit-learn.

**5. Data Visualisation:**
- **Steps:** Create interactive dashboards to visualise data insights and trends, aiding in decision-making for the marketing campaign.
  - **Dashboard 1 - Modelling & Analysis:**
    - *Modelling Performances:* Displays key performance metrics including the accuracy score of the model used to predict consumer behaviour.
    - *Cumulative Gain Chart:* A visual comparison of the model’s performance versus a random model in targeting potential buyers.
    - *Confusion Matrix:* Illustrates the prediction performance by showing true positive, true negative, false positive, and false negative rates.
    - *Profit Analysis by Consumer Percentage:* Analyses the profitability of marketing campaigns targeted at different percentages of consumers within the loyalty program.
    - *Impact Analysis:* Evaluates the effectiveness of marketing strategies by assessing the percentage of willing buyers, total buyers reached, and non-buyers avoided across various consumer segments.
  - **Dashboard 2 - Demographics:**
    - *Loyalty Analysis:* Displays the distribution of loyalty classes, spend, and frequency among customers, allowing for a better understanding of customer segmentation.
    - *Gender and Age Distribution:* Provides insights into the demographic breakdown of the customer base by gender and age.
    - *Regional Distribution:* Shows the distribution of customers across different regions and TV regions, offering insights into geographical customer segmentation.
    - *Cluster Group Score:* Analyses customers based on cluster scores, providing a deeper understanding of customer segments.
    - *Affluence Score:* A distribution chart depicting the affluence score across customers, which helps in identifying high-value customer segments.
- **Tools:** Tableau, Figma.

**6. Interpretation and Reporting:**
- **Steps:**
  - **Insight Generation:** Interpret the dashboards to derive actionable insights and identify key patterns.
  - **Report Creation:** Compile a comprehensive report summarising the analysis, findings, and strategic recommendations for the marketing campaign.
- **Tools:** Microsoft Word, Microsoft PowerPoint.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) for details.

## Acknowledgements
This project is an adaptation of the concepts and methodologies taught by SKILLCATE on YouTube. Special thanks to SKILLCATE for their guidance and instructional videos.

### Original Tutorial
- <b>[SKILLCATE YouTube Channel](https://youtu.be/g7hEPopJ4MY?si=6rqY0gc6PiNl12Sm)</b>

### Disclaimer
This project is based on a fictional company, ABC Supermarket. All data, analyses, and insights presented here are for learning purposes only and do not reflect any real-world business entity or data.

Please note that this project is an adaptation of the concepts and methodologies taught by SKILLCATE. Any code, data, or content not directly from SKILLCATE is original work created for this project and is covered under the MIT License.

## Contact Me!
For any questions or feedback regarding this project, feel free to reach out:
- Email: jiahao.shao30@gmail.com
- LinkedIn: <b>[Jiahao Shao](https://www.linkedin.com/in/shao-jiahao)</b>
