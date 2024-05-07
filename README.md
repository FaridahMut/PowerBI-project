# Data Professional Survey Breakdown- PowerBI project

## Introduction
The project uses a dataset collected using a survey website from professional in different industries. The professionals answered several questions ranging from the type of industry they work in, the estimated salary, programming language they use, how satisfied they are in their current jobs and work-life balance, how difficult it was to break into the data analysis field to questions about their ages etc.
no personal data was collected foe example the email addresses are anonymous.

## Objectives
Is to indentify people in different roles and how much they earn.

## Questions
1. What is the total number of of people who participated in the survey?
2. What is the average age of the participants?
3. What is the salary in the various professions?
4. What is the average salary between male and female?
5. Which programming language is the favourite across the different job titles?
6. Is salary for the same profession the same or different across different countries?
7. How happy are the participants in their jobs and in terms of work-life balance?
8. How difficult is it to break into the data analysis field?
   

PowerBI data process;
1. Data Cleaning
2. Visualization

## Data Cleaning
1. First step was to delete some unnecessary columns that did not have any data and did not interfere with the overall integrity of the data. Delete columns from browser all the way to referrer.
2. Clean and standardize the "what best describes your career" column as their were many roles under "other". To navigate these, I choice 6-7 major careers and classified the rest under "other", to reduce the numerous careers during visualization process.
3. Split the career row using delimeter "(" to get columns with "Other" and the rest of the careers
4. Clean and standardize the "programming language" column too to leave the major languages,that could be selected, and the "other" options
5. Clean and standardize the "country" and "industry work in" as above. 
6. Clean, transform and standardize the "estimated salary" column by duplicating the columns and splitting the salary ranges into two, get the average and use this as the salary for the profession. Although this is not an accurate indication, it will help to get insights from the data. **NOTE** Ensure the columns are whole numbers so Average calculation can be applied.

## Visualization
1. Setup **cards** to give a quick glance of important data like the total number of survey partcipants,**630 ** and their average age **29.87**.
2. A **stacked bar chart** to show the average salaries in the various professions.
3. Used a **piechart** to compare the average salary between meale and female.
4. A **stacked column chart** to show the favorite language across the different professions and the number.
5. Use a **tree map** to show the different countries, and when clicked the average salary of each profession in that country changes.
6. Use a **gauge** to visualize the degree of satisfaction in terms of work-life balance. The score from the data is **5.74** score on **work-life balance**
7. Used a **gauge** to visulaize the degree of satistaction with their salaries, score of **4.27**.

<img width="629" alt="PowerBI_visualization" src="https://github.com/FaridahMut/PowerBI-project/assets/160776452/b68233a7-ef52-4f15-a849-fb2e4fd825cd">
