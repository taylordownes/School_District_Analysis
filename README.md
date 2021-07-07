# School_District_Analysis
## Overview
This mock analysis is centered on analyzing school district data including school funding and standardized test scores to make strategic decisions at the school and district level. The goal is to aggregate the data and show trends in school performance. Using the students_complete.csv file as our dataset, we were informed that the dataset showed evidence of academic dishonesty specifically for Thomas High School 9th grade reading and math scores. Our analysis consists of the following deliverables:
1. Replacing the Thomas High School ninth grade test scores with NaNs while keeping the rest of the data intact.
2. Performing a school district analysis that includes calculating average scores, passing percentages, and more based on grade, school, school type, and school budget. 

## Results

- How is the district summary affected?

    - After calculating the averages for math, reading, and passing scores and assembling them into a DataFrame, we get the following results:

    ![image](https://user-images.githubusercontent.com/84201614/124525783-26412a00-ddc6-11eb-9411-f0c83fd27c9d.png)
      
    - We can see that Charter schools have a higher math, reading, and overall passing score compared to District schools.

- How is the school summary affected?
    
    - Below are the top five overall passing schools based on the generated school summary:
    
    ![image](https://user-images.githubusercontent.com/84201614/124600068-f7f63580-de2b-11eb-8619-de210d265e5b.png)

    - We can see that Cabrera High School has the highest overall passing percentage and is a Charter school.
    
     
    - Below are the bottom 5 overall passing scores:

    ![image](https://user-images.githubusercontent.com/84201614/124600515-6a671580-de2c-11eb-8798-b06663fbaf31.png)

    We can see that Rodriguez High School has the worst overall passing percentage and is a District school. They also have an extremely large budget at $2.5 million, which is       larger than the average total budget spending at $1.6 million.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    Replacing the ninth grade scores with NaNs for Thomas High School had the following effects:  

  - Math and reading scores by grade
  
  - scores by school spending 
  
  - scores by school size
  
  - scores by school type




## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
