# School District Analysis

## Project Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth. We are tasked with a list of the following to resovle and investigate this issue of irregularity.
1. Allow the school board to uphold the state-testing standards.
2. Disregard ninth grade math and reading scores at Thomas High School
3. Determine how much this action will affect the Data that was already completed
4. Present findings to Maria, her supervisor and the school board.

## Resources
- Software: Jupyter Notebook
- PyCitySchools_Challenge_starter_code.ipynb
- Files: students_complete.csv
         schools_complete.csv
         
## Results
- Replacing the 9th grade reading and math score at Thomas High School with NaN. Fig.1![Fig 1](https://user-images.githubusercontent.com/78861458/111173718-40d46680-857d-11eb-93bc-0f4392d5faa3.png)


- Summary of the DataFrame for ths school district Fig. 2![Fig 2 1](https://user-images.githubusercontent.com/78861458/111173429-05d23300-857d-11eb-880e-2d834a27a5ea.png)


- Summary of each School without the 9th grade Fig 3![Fig 3](https://user-images.githubusercontent.com/78861458/111174976-5007e400-857e-11eb-83e4-9d07f5f4f1b6.png)


- High and Low Performing Schools Fig. 4![Fig 4](https://user-images.githubusercontent.com/78861458/111175538-e76d3700-857e-11eb-89c1-f995de2b2d5e.png)


- Scores by school spending Fig. 5![Fig 5](https://user-images.githubusercontent.com/78861458/111177414-93635200-8580-11eb-84cd-cfdc296be510.png)
                                 ![Fig 5 2](https://user-images.githubusercontent.com/78861458/111315548-dd0f7380-8638-11eb-9036-431e56355bbe.png)


- Scores by school size Fig. 6![Fig 6](https://user-images.githubusercontent.com/78861458/111178107-35833a00-8581-11eb-8009-6b474ff6451a.png)


- Scores by school type Fig. 7![Fig 7](https://user-images.githubusercontent.com/78861458/111178497-990d6780-8581-11eb-87b2-2c917ff675f3.png)


## Summary
Both math and reading scores were replaced using .loc() function as shown in Fig 1. The results to the school district analysis are as follows:

1. A significant reduction in Thomas High School students passing math reading and the overall passing both subjects

2. Fig. 2 the per_school_summary_df, the data frame that gives the summary for the data involve, changes to the Thomas High School from the original performace for testing
   but only to one (1) significant decimal place.

3. In the budget the performace based on students passing all three (3) areas, significant changes resulted. the ranges for the spending per student can seen shown in Fig. 5
   and Fig. 5.2

4. Changes to the analysis did not move Thomas High School from the top perfroming schools see Fig 4

