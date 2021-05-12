# data_bootcamp_final_project

This  project  was  completed  by Claire Park in  partial  fulfilment  of  ECON-UB.0232,Data Bootcamp,  Spring 2021.  I certify that the NYU Stern Honor Code applies to this project. In particular, I have:

Clearly  acknowledged  the  work  and  efforts  of  others  when  submitting  written  work  as  our  own.The  incorporation  of  the  work  of  others–including  but  not  limited  to  their  ideas,  data,  creativeexpression,  and  direct  quotations  (which  should  be  designated  with  quotation  marks),  or  para-phrasing  thereof–  has  been  fully  and  appropriately  referenced  using  notations  both  in  the  textand the bibliography.

And I understand that:

Submitting the same or substantially similar work in multiple courses, either in the same semesteror in a different semester, without the express approval of all instructors is strictly forbidden.

I acknowledge that a failure to abide by NYU Stern Honor Code will result in a failing grade for the project and course.

# Project Description

The project is about making a prediction on who will more likely to have a stroke using the historical data. There are 11 clinical features for predicting stroke events in the data. You can find the details for each column below:

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient

I will build a few different models to predict stroke events and compare their performances.
