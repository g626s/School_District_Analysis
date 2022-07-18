# School_District_Analysis

# Overview of the school district analysis: 
In our previous analysis with our client Maria who is the chief data scientist for a school city school district, we assisted in providing insight and analyze data on student funding and student standardized test scores. Throughout the process phase of the project we were given access to every student's math and reading scores as well as various information on the schools they attend. Through the analysis we then aggregated the data and showcased trends in school performance. The initial analysis assisted the school board and superintendent in making decisions regarding the school budgets and priorities. For the task, our team was well informed and aware of the Family Educational Rights and Privacy Act of 1974 that protects the privacy of student educational records so data privacy and integity was crucial in the analysis. 

From the previous analysis our team submitted, the school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have requested our client Maria's assistance. She has requested the objective of this project to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the we replaced the math and reading scores, our client also requested to repeat the school district analysis that you did in this project and write up a report to describe how these changes affected the overall analysis.

# Results: 
- How is the district summary affected?
    - The district summary is affected since the 9th graders at Thomas High Schools’ data was in null data (NaN). This null data recalculated the percentage of of passing math, passing reading, and the overall passing percentage in this category. It is also important to note and point out the total count of students was unchanged since the value was based on the count of Student IDs that was not turned into null data. 
    - With the analysis adjusted, the removal of the selected test scores had a slight impact on the district summary dataset with less than a 1% difference. ![Screen Shot 2022-07-17 at 8 09 22 PM](https://user-images.githubusercontent.com/107281474/179445869-717e7566-afe7-4b5b-9afe-49b09075ca68.png)

    - <img width="803" alt="Screen Shot 2022-07-17 at 2 25 20 PM" src="https://user-images.githubusercontent.com/107281474/179443205-50d1c092-4441-4358-8a95-e46ecb568d9d.png">


- How is the school summary affected?
    - In the original school summary analysis, Thomas High School had a estimated 66.9% passing math percentage, 69.6% passing reading percentage, and 65% overall passing rate percentage that raised concerns with the school board and the superintendent. After careful analysis and calculation of the total number of 10th-12th graders as the new denominator, the testing data for Thomas High Schools was adjusted and reanalyzed. 
    - <img width="788" alt="Screen Shot 2022-07-17 at 2 45 16 PM" src="https://user-images.githubusercontent.com/107281474/179443309-45f56b1b-6b7a-4e66-b499-372a66db898d.png">
    - <img width="796" alt="Screen Shot 2022-07-17 at 9 01 32 PM" src="https://user-images.githubusercontent.com/107281474/179443551-5458317c-b9c2-4af2-ab0a-02b3acff20be.png">
    - The removal of the 9th grade students at Thomas High School from the school summary dataset had a major significant change and percentage shift from passing math and reading percentage to overall passing percentage. 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Replacing the ninth graders' math and reading scores affected Thomas High School's performance relative to the other schools by shifting the school’s rank all the way to 2nd place in top five schools. 
    - ![Screen Shot 2022-07-17 at 8 04 29 PM](https://user-images.githubusercontent.com/107281474/179443678-a32f54c7-19b5-4688-9a6f-5423667ae783.png)

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
      - With the new analysis replacing the math and reading scores for ninth graders at Thomas High School, the values in the ninth grade column for the row of Thomas High School has been replaced with null values (NaN).
      - ![Screen Shot 2022-07-17 at 8 09 22 PM](https://user-images.githubusercontent.com/107281474/179445885-4c4bc1b7-461e-4a85-b017-f2363ff12530.png)
      - ![Screen Shot 2022-07-17 at 8 09 55 PM](https://user-images.githubusercontent.com/107281474/179445892-28448d68-5f27-4db8-a2cd-b77a8437731e.png)

    - Scores by school spending
      - Replacing the ninth grade scores from Thomas High School had no significant effect on the rank of the school in the given school spending DataFrame. Thomas High School is placed into the $586-630 school spending range (per student).
      - <img width="939" alt="Screen Shot 2022-07-17 at 8 21 04 PM" src="https://user-images.githubusercontent.com/107281474/179446263-7e9dd4df-c45f-475d-89e7-49c1d5ce16e8.png">
      - <img width="926" alt="Screen Shot 2022-07-17 at 8 21 20 PM" src="https://user-images.githubusercontent.com/107281474/179446043-d3a7474a-f689-44e7-88d0-9e4b7d3ee76e.png">

    - Scores by school size
      - Replacing the ninth grade scores from Thomas High School had no significant effect on the rank of the school in the given school size DataFrame. Thomas High School is placed into the Medium (1000-1999) school size range.
      - <img width="923" alt="Screen Shot 2022-07-17 at 8 22 31 PM" src="https://user-images.githubusercontent.com/107281474/179446364-f6c39406-72ea-4e99-a3a8-52435cf4e0c2.png">

    - Scores by school type
      - Replacing the ninth grade scores from Thomas High School had no significant effect on the rank of the school in the given school type DataFrame. Thomas High School’s school type is a Charter.
      - <img width="914" alt="Screen Shot 2022-07-17 at 8 26 23 PM" src="https://user-images.githubusercontent.com/107281474/179446399-2d851e0a-edbc-442f-bd49-b9e55817f9b4.png">
      - <img width="928" alt="Screen Shot 2022-07-17 at 8 26 34 PM" src="https://user-images.githubusercontent.com/107281474/179446443-7709aa70-bebb-4a46-9d4b-84d0fba85bb8.png">


# Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The charter school Thomas High Schools’s overall passing rate from approximately 65% to 91%
2. The charter school Thomas High Schools’s passing reading and math scores rose significantly as well.
3. In the ninth grade level for Thomas High School, the data and information will now display “NaNs”.
4. The data and information at grade level in the school district will now appear as "NaN" in reports for the 9th grade students at Thomas High School. 
