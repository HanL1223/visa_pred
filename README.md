# visa_pred

US Business sector has long facing high demand of human resources in various skillsets.

The Immigration and Nationality Act (INA) of the US permits foreign workers to come to the United States to work on either a temporary or permanent basis, under visa such as H1B, H2B.

In FY 2016, the immigration office processed 775,979 employer applications for 1,699,957 positions for temporary and permanent labor certifications. This was a nine percent increase in the overall number of processed applications from the previous year. The process of reviewing every case is becoming a tedious task as the number of applicants is increasing every year.

# Objective
The increasing number of applicants every year calls for a Machine Learning based solution that can help in shortlisting the candidates having higher chances of VISA approval. The objective is to analyze the data provided and, with the help of a classification model:

Facilitate the process of visa approvals.
Recommend a suitable profile for the applicants for whom the visa should be certified or denied based on the drivers that significantly influence the case status.

# Implementation
In this project, I conducted a EDA on the dataset for it's trend and pattern, preprocessed the dataset using its original form and a upsampling form using SMOTE(to tackle label unbalance). Finally conduct model selection, fine tune and testing.

# Evaluation
In this task, we wish to have an 'even' distribution towards the trade off since skew to either side will require a human review in detail, thus we will mainly focus on model's F1 score.
