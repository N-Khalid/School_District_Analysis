# School_District_Analysis

## Overview of the school district analysis

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

Deliverable 1: Replace ninth-grade reading and math scores

Deliverable 2: Repeat the school district analysis

Deliverable 3: A written report for the school district analysis (README.md)

## Results

- How is the district summary affected?

The district summary was minimally affected by the changes in the data when removing NaN values as shown below. None of the datapoints were affected by significantly.

![District Summary](https://user-images.githubusercontent.com/103234661/189501372-34bb966f-ce99-43b1-8311-447200288ddf.png)

- How is the school summary affected?

We can see how the changes affected the school summary by looking at the before and after of Thomas High School. 

Before:
![School Summary 2](https://user-images.githubusercontent.com/103234661/189503701-4e010a2e-92d2-46e9-abab-b47aa6e30c74.png)
After:
![School Summary 1](https://user-images.githubusercontent.com/103234661/189503700-fa371b4c-f505-4bc6-9972-2928125301ad.png)

The math, reading and overall passing grades have drastically changed.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas Highschool was ranked overall 2nd initially. After they drop down to 8th place in overall passing %.

#### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

Math Scores
![Math Scores](https://user-images.githubusercontent.com/103234661/189505301-18fcac5c-aaee-438a-83d4-411caec59444.png)

Reading Scores
![Reading Scores](https://user-images.githubusercontent.com/103234661/189505304-85180e18-1ac9-4947-969d-a9098b9f873b.png)

Both math and reading scores for 9th grade show up as NaN values for Thomas Highschool

- Scores by school spending

![Spending Scores](https://user-images.githubusercontent.com/103234661/189505425-071f78d2-3c30-4476-91a1-f33be7038082.png)

There is no change in the spending scores for Thomas Highschool.


- Scores by school size



- Scores by school type

Before:
![before school type scores](https://user-images.githubusercontent.com/103234661/189505674-28c6b394-493a-45c9-8f8d-6bf9b1914067.png)

After:
![After school type scores](https://user-images.githubusercontent.com/103234661/189505678-1f33fe23-e830-49bc-95e0-2046dd1f987e.png)





## Summary
There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
