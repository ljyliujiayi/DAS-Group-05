# DAS-Group-05
## Introduction
This project analyses which household related variables influence the number of poeple living in a household in Zasmboanga Peninsula of the Philippines.

## Files
'dataset05.csv': the dataset we analysed

(https://github.com/ljyliujiayi/DAS-Group-05/blob/main/dataset05.csv)


'Group_05_Analysis.qmd': R code for GLM analysis.

(https://github.com/ljyliujiayi/DAS-Group-05/blob/main/Group_05_Analysis.qmd)



'Group_05_qmd.pdf': PDF document created by rendering 'Group_05_Analysis.qmd'

(https://github.com/ljyliujiayi/DAS-Group-05/blob/main/Group_05_qmd.pdf)

## Variables
• Total.Household.Income – Annual household income

• Region – Zasmboanga Peninsula of the Philippines

• Total.Food.Expenditure – Annual expenditure by the household on food

• Household.Head.Sex – Head of the households sex

• Household.Head.Age – Head of the households age in years

• Type.of.Household – Relationship between the group of people living in the house

• Total.Number.of.Family.members – Number of people living in the house

• House.Floor.Area – Floor area of the house in m^2

• House.Age – Age of the building in years

• Number.of.bedrooms – Number of bedrooms in the house

• Electricity – Does the house have electricity? (1=Yes, 0=No)

## Analysis procedure
1. Data wrangling : Convert categorical variables, Log transformation of skewed variables
2. Explanatory data analysis : Visualized and statistically analyzed data
3. Model construction : Build four generalized linear models (GLM)
4. Model selection : Remove variables by p-value and select the best-fitting model by AIC value
5. Model prediction performance : Check the prediction performance on the test set
6. Conclusion : Summarize significant variables and their impact on the number of people living in the house

## Instructions
1. Open 'Group_05_Analysis.qmd' in Rstudio.
2. Run code to conduct analysis.
3. View analysis report via 'Group_05_qmd.pdf'.

## Contact information
For any questions, feel free to contanct Jiaming Lu at 2884504L@student.gla.ac.uk or Jiayi Liu at 2873318L@student.gla.ac.uk.
