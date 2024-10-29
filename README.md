# Modeling Agri-finance Credit Risk with Data & Machine Learning

## Table of Contents
- [Project Overview](#project-overview)
- [Project Problem](#project-problem)
- [Project Objectives](#project-objectives)
- [Project Steps](#project-steps)
- [Key Results](#key-results)
    - [Power BI Dashboards](#power-bi-dashboards)
    - [Business Implications](#business-implications)
- [Additional Useful Information](#additional-useful-information)
    - [Acknowledgements](#acknowledgements)
    - [Software Stacks Used](#software-stacks-used)
    - [Inquiries](#inquiries)

## Repository Structure
* **Power BI Visualizations**: Dashboards created for the project.
* **Project Presentation**: Slides summarizing the project.
* **Readme File**: Overview of the project.
<br></br>
<br></br>

## Project Overview:
* This project was developed during my data science internship at Agriculture Finance Services Corporation (AFSC) in summer 2024. I was also a project manager and led a team of 4 interns (Seth Graham, Kiana Mailloux, Lesley Brausse, and myself) for a project that investigates the impact of data can bring to the company.
* The slides in this repository includes my part of the project, where I used data to develop predictive models to model credit risk in AFSC.
<br></br>

## Project Problem:
* Agricultural finance (agri-finance) deals with unique challenges like weather dependency, seasonal income, and other agricultural factors, which traditional finance models struggle to address.
* This project demonstrates an end-to-end data-driven credit risk modeling process using Python, SAS, SQL, and Power BI.
* It aimed to model and reduce exposed credit risk for an agri-finance corporation by developing tailored predictive machine learning models, but this concept can also be applied to other companies from other industries as well!
<br></br>

## Project Objectives:
1. Identify key factors of causing loan defaults
2. Predict which loans are likely to default in the future
3. Improve anomaly detection by exploring machine learning methods
4. Communicate actionable insights extracted with Power BI dashboards
<br></br>

## Project Steps:
1. **Data Collection**
     * Formulated datasets from internal loans and external macroeconomic factors using SAS and SQL. 

2. **Data Preprocessing**
     * Cleaned, imputed, and transformed data for future analytical and prediction purposses.
     * Adopted an unsupervised learning approach by using clustering techniques to impute some missing data.
3. **Exploratory Data Analysis (EDA)**
     * Analyzed data to observe any hidden key trends, patterns, and relationship in the dataset.
4. **Feature Engineering**
     * Created new features from existing data to further improve the performances of machine learning models built later.
5. **Building Machine Learning Models**
     * Developed AI-empowered predictive models to forecast the default outcomes for agricuture loans.
     * Machine Learning Models:
         * Decision trees
         * Random forests
         * Extreme gradient boosting trees (XGBoost)
         * Extreme gradient boosting random forest (XGBRF)
         * Feedforward Neural Network
6. **Model Optimization**
     * Built semi-automated pipeline to tune the built models for optimal predictive performances.
7. **Exploring Advanced Machine Learning Techniques**
     * Applied data resampling techniques and explainable AI (XAI) methods for model optimization and explainability.
8. **Power BI Dashboards**
     * Created interactive Power BI dashboards to present actionable insights obtained to project stakeholders.
<br></br>

## Key Results
1. **Identified four critical factors influencing loan defaults** (accrued interest, arrear interest, total amount due, proportion of remaining payment)
     * Finding them help both agri-finance corporations and their clients to be more aware about their impact, thus better preventing loans from resulting in default.

3. **Achieving a 97.5% accuracy in predicting loan defaults**
     * The models I build can predit 975 out of 1000 loans' default outcome correctly, allow agri-finance corporations to assess their own credit risk.
5. **Improved default loan detection by 6.5%** with data resampling techniques.
     * Enhanced anaomaly detection allow agri-finance corporations to prevent them from happening, avoid potential financial losses. 
7. Produced interpretable and credible AI solutions with **explainable AI (XAI)** methods.
     * Promote digital trust and recognition of data-driven decisions for both agri-finance coprorations and their clients.
9. Summarized & reported project findings in **Power BI dashboards**.
     * Transform numerical findings into actionable insights and communciate them in an aesthetic manner. 
<br>

|                          | Decision Tree | Random Forest | Extreme Gradient Boosting Trees (XGBoost) | Extreme Gradient Boosting Random Forest (XGBRF) | Neural Network |
|--------------------------|---------------|---------------|-------------------------------------------|--------------------------------------------------|----------------|
| **Training Accuracy**    | 98.16%        | 97.99%        | 97.49%                                    | 95.65%                                           | 97.34%         |
| **Validation Accuracy**  | 97.43%        | 97.53%        | 97.37%                                    | 95.68%                                           | 97.32%         |
| **Testing Accuracy**     | 97.40%        | 97.49%        | 97.33%                                    | 95.60%                                           | 97.28%         |
| **AUC-ROC**              | 0.81          | 0.96          | 0.92                                      | 0.78                                             | 0.90           |

<br></br>

## Power BI Dashboards
![DB 1](Power_BI_Visualziations/Summer_Project_Dashboard(AFSC).pptx.jpg)
* A Power BI dashboard is created with the intentation to be viewed for the agri-finance coporation internally. It focuses on highlighting:
    * The underlying business intellgence insights about the default loan based on other important factors.
    * The predictive performances and insights extracted from the products built in this project.
    * The potential impact of default loan towards the corporation itself, especially during COVID-19.

<br>

![DB 2](Power_BI_Visualziations/Summer_Project_Dashboard(AFSC).pptx.png)
* Another Power BI dashboard is created with the purpose of externally sharing insights to the agri-finance corporation's customers, by providing:
    * Data-empowered insights from this project that the clients are most interested about.

    * Common factors of causing default loans so the clients be aware of.
    * Tips for clients to avoid having their loans to become default.
    * Promises on proper data usage to advaocate data sharing and gain cleints' digital trust.
<br></br>

## Business Implications:
* By applying the following assumpetions:
   * The optimized models can retain their predcitive accuracy in forecasting the default outcomes of new loans.

   * Only 10% of predicted default loans can realistically be prevented from defaulting with our model.
* If the project built models are applied to forecast all loans for AFSC in the fiscal year of 2023, then:
    * 4.4% of credit risk exposed are reduced.

    * Translating to $12 million in potential financial loss savings.
<br></br>

## Additional Useful Information
### Acknowledgements:
* My teammates for this project: Seth Graham, Kiana Mailloux, and Lesley Brausse 
    * Thanks for going crazy with me! This project does not go far without you all!

* My project sponsor: Jesse Cole
    * Thanks you so much for your guidance and feedback on this project!
* My supervisor: Saroj Aryal
    * Thanks for your guidance and feedback during my internship! I applied as many things I learned from you on this project!
<br></br>

### Software Stacks Used:
| Category                  | Tools                                       |
|---------------------------|---------------------------------------------|
| **Programming Languages** | Python, SAS, SQL                           |
| **For Data Preprocessing**| Pandas, NumPy, SciPy                       |
| **For Machine Learning**  | Scikit-learn, xgboost, TensorFlow, Keras   |
| **For Data Visualization**| Power BI, Matplotlib, Seaborn              |
| **For Project Management**| Trello, Agile, Scrum                       |

<br></br>
### Inquiries:
* if you want to...
     * Know more about my project.

     * Read my academic capstone project report that investigated the application of data-driven decision-making in agri-finance. 
     * Collaborate with me for something promising :)
     * Have a simple coffee chat with me
* Then feel free to contact me through my linkedin (on my github homepage)
