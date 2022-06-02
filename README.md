# School District Analysis

## Project Overview
A data scientist form city school system Maria is responsible for analyzing the information from a variety of sources in a variety of formats. We are given certain tasks to help Maria to analyze data on student funding and student analyzed test scores. These insights are used to take informed and strategic decisions at the school and district level . Below are the tasks given to us
 1. Clean the data by ensuring there are no null values and removing any prefixes or suffixes that are not appropriate
 2. Calculate the below metrics
     1. Calculate the total number of students
     2. Get the total number of schools
     3. Calculate the total budget
     4. Calculate the percentage of reading, math and overall passing
     5. Getting the top 5 and bottom 5 performing schools
     6. Getting the grade level scores
     7. Calculate the statistics based on spending , school size and type of school
But later Maria and her supervisor have been notified that there was some evidence on academic dishonesty; specifically, reading and math scores for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once we replaced the math and reading scores, we have to repeat all the above tasks

## Resources
- Data Source : schools_complete.csv, student_complete.csv
- Software    : Python 3.8, Visual studio code, 1.67.2

## Results 
Below are the results of the following before and after the change to Thomas High School 9th grade scores
- District summary
   - The image of the district summary before the change is as below
   
     <img width="700" alt="image" src="https://user-images.githubusercontent.com/104597335/171520109-bf2e4374-2e18-4dfa-8f02-09bae8f5ed45.png">
   - The image of the district summary after the changes is as below
   
     <img width="700" alt="image" src="https://user-images.githubusercontent.com/104597335/171520137-35102b7e-1233-48b3-a81b-8dcb900f9858.png">
    As we can see from the images there is no change to the number of schools, total students and budget as expected since there is no change to the schools, students     and budget. However there is a slight variation to the passing math %, passing reading % and overall passing percentage.
- School summary
    - The image of school summary in particular to Thomas High School before the change is as follows
    
      <img width="700" alt="image" src="https://user-images.githubusercontent.com/104597335/171520292-8e5d2a0b-55fa-4d96-b400-0abe8255cc7f.png">
    - The image of school summary in articular to Thomas High School after the change is as follows. 
    
      <img width="700" alt="image" src="https://user-images.githubusercontent.com/104597335/171520343-8f869e37-1b34-440e-8081-3ba651e8d5ed.png">
    As we can see from the images there is no change to the type of school. the number of students and the budget as expected. But there is a vast change to the           passing math , reading and overall passing percentages
- Change of performance for Thomas High School before and after change is as follows
    - Passing math percentage before the change was 66.91% and after the change was 93.86%
    - Passing reading percenatge before the change was 69.66% and after the change was 96.53%
    - Overall passing percenatge before the change was 65.07% and after the change was 90.58%
    Based on the above data we can say that after the update the performance in accordance to all the three percenatges i.e, math, reading and overall has been             increased. Also now the Thomas High School is in the Top 5 performing schools
- Effect of change on "Math & reading scores by grade"
    - Since the change is only related to the 9th grade scores we can see that the score for 9th grade is shown as NaN for Thomas High School for both Math and Reading 
    Math scores by grade-
    
    <img width="600" alt="image" src="https://user-images.githubusercontent.com/104597335/171520909-5f37d4e8-92f7-4f17-a507-3f7ad8c73a84.png">
    
    Reading scores by grade -
    
  <img width="600" alt="image" src="https://user-images.githubusercontent.com/104597335/171520763-83c21607-6725-4a30-a79e-44f2cd5e83ce.png">

- Effect of change on "Spending summary"
   - When we look at the data of spening summary there is a change to the "$631-645" range spending bin at the 100ths place. However when we format the data we dont        see this difference.
- Effect of change on "Size summary"
   - When we look at the data of size summary there is a change to the "Medium(1000-1999)" range size bin at the 100ths place. However when we format the data we dont      see this difference.
- Effect of change on "Type summary"
   - When we look at the data of type summary there is a change to the "Charter" school type bin at the 100ths place. However when we format the data we dont see this      difference.

## Challenge Summary
Finally when we take a close look at the data there is slight change to the passing percentages of District summary, spending summary,size summary and type summary at the 100ths place. However there is vast difference in these percentages at the school summary level for Thomas High School as well as increase in the performance of this school . The grade level data for 9th grade for Thomas High School has been updated to NaN.
