# Predicting Diabetes with Various Modeling Techniques

This app was developed to allows users to explore the relationship between various health measuremnts (such as BMI, or age) and the occurrence of diabetes. Furthermore the app contains a data exploration tab to analyze distributions between the diabetic and non-diabetic groups to help identify useful predictors. 

The [data](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset?resource=download) contains 768 patients with information on number of pregnancies, blood glucose levels, blood pressure, skin thickness, insulin levels, BMI, pedigree function, age and whether or not they developed diabetes. 

## Shiny app Functions

- Data exploration: compare distributions of predictors between diabetic and non-diabetic groups to identify useful predictors.
- Logistical Modeling Tab - Allows users to select predictors and calculates test error and model output.
- Naive Bayes Model - Allows users to select predictors and calculates test error and model output.
- QDA Model - Allows users to select predictors and calculates test error and model output.
- LDA Model - Allows users to select predictors and calculates test error and model output.
- Parttree Model - Allows users to select 2 predictors of interest and shows decision tree classification areas in comparison to actual data points.  

The Shiny app includes a data exploration tab and 5 modeling tabs with test error accuracy. The five models included are a Logistical, Naive Bayes, QDA, LDA and parttree models. 



  
## Contents
- `final_report.qmd/final_report.html` - Project Report
- `final_project.qmd` - Shiny App
- `final_pres.qmd` - Brief Class Presentation
- [Blog Post](https://jaxlub.github.io/Data-Visualization-Blog/posts/final_proj/) - Blog post highlighting a few features of the app
