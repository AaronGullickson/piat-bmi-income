# Data Source Description

For this analysis, you will be using an extract of data from Wave 4 of the [National Longitudinal Survey of Adolescent to Adult Health](https://addhealth.cpc.unc.edu/) (Add Health). Add Health began tracking a cohort of adolescents in 1994-95 and has continued to track these individuals as they have aged with follow up waves. We will be using some data from wave 4, which was conducted in 2008 when these individuals were 25-34 years of age.

From the full data, I have extracted and recoded the following variables for our use as an analytical dataset. To load this dataset in R, you just need to run the setup code chunk in the full_report.Rmd R Markdown document. The name of the dataset in R is `addhealth`.

-   **bmi**: This is the body mass index of the respondent. BMI is measured as $kg/m^2$. It basically is a measure of how much someone weighs but also accounts for differences in height. This is our key dependent variable.
-   **fast_food**: The number of times in the last week that the respondent ate at a fast food restaurant.
-   **sweet_drinks**: The number of sweetened drinks the respondent has consumed in the past week.
-   **hh_income**: Household income of the respondent. This is measured in brackets of income, so you should treat it as an ordinal variable. This is the key independent variable.
-   **education**: The highest degree the respondent has received.
-   **gender**: The gender of the respondent.
-   **age**: The age of the respondent.
