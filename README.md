# Momentum LLC Selection Keras Algorithm

- - -

## Overview of Momentum & Model

What is Momentum?
    - Momentum is one of the University of Minnesota Rochester's (UMR) Living Learning Communities (LLC) that is starting for term Fall 2026. LLCs group students into a cohort that live in proximity to one another and organize extra-curricular & co-curricular activities to boost community building and academics on campus. Momentum's mission is to assist students that require additional academic support in the subjects of math and science.

- Purpose
    - The purpose of the neural network is to predict if an entering student will need additional support in math and/or science. Students identified will be reviewed manually for verification of fitness and may be placed into the Momentum LLC for AB testing of student performance with identified students not placed into the Momentum LLC.

- What is being predicted?
    - Depending on the run configuration, math (HELPMATH) or science (HELPSCI) are run separately and funneled the field called Help_Y. The trained model will output a value between 0 & 1 for each student row.

- Goal
    To create a model that can recognize patterns between possible need for academic support in math and/or science and data pertaining to secondary school performance, entrance exam performance, biographical, and select other data sources. We will be passing these correlations and a list of identified students in the form of 3 lists (might need help in math, might need help in science, and might need help in math and science) to our academic team for cohort forming and AB testing.

- Measuring
    After the model is built, it will be tested on a subset of testing data and a value between 0 & 1 will be predicted and assigned by the model in the field " Predicted_Help_Y" and that will be compared to the entering student’s transcripts & ALEKs math assessment records to verify accuracy via human secondary review.
