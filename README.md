# Final_Project
IS590PR Spring 2019. Top-level repository for student project forks

The detailed instructions for the Final Projects will be in the course Moodle.

Team members:
Tianqi Chen
Yanan Shen

Title: 

Analysis of the factors affecting the trend of talents in the world and the success rate of individual immigration

Part 2 

Purpose:

For this part, we mainly focus on how skill penetration rate impacts the net migration rate of skill migration and industry
migration from 2015 to 2018.

Hypotheses:

Skill peneration rate has positive correlation relationship with net migration of skill migration and industry migration

Design reasoning:  
1.Merge 4 dataset (industry migration-- industry needs skills--skill migration--skill penetration rate)
  Be more convenient to establish the relationship between the skill penetration rate and net migration rate of skill and
  industry migration.
2.Calculate the difference 
  This step is to calculate the difference between the 2015 net per 10K  and 2018 net per 10K  and the difference between the
  2015 skill penetration rate and 2018 skill penetration rate to know the net migration increase or decrease.
  Net per 10k: with different industry section and name, the net migration rate of skill migration.
3.Drawing plot by using calculated difference value
4.Find the oulier of skill penetration rate difference 
  This step is based on the third step. The outlier could be the further demonstration of hypothesis 
  
Analytical Summary of our findings:

  Skill migration line chart and pie chart:
  positive correlation relationship
  Abnormal Value: soft skills (like leadership, problem solving). Although it is more and more important and needed by each
  industry, it still not belong to thigh-skilled immigration.
  The pie chart demonstrate although the difference trend between skill penetration rate is positive correlated, the total
  number of people who could success skilled migration is not have the positive correlated as the trend. It still have the
  situation that although the skill penetration is increase, the number of the skilled migration is decreasing
 
  Industry migration line chart and pie chat:
  positive correlation relationship 
  Abnormal industry section is professional scientific and technical activities. We could find that the skill presentation is
  high but the net 10k is low explained by upper outlier scatter plot

  Outlier:
  The upper outlier is calculated by skill penetration rate. we also could see that the net 10 k for this value is lower than
  0 which means the number people who belongs to this category is reducing but the this skill is increasing. This could 
  totally explained why profession industry has high skill penetration but low net migration rate.
  For the lower outlier, it is totally different, we can see that most point is below 0 which means the skill rate is lower 
  and the net migration is lower which is the positive relationship,especially people who have skill on manufacturing 
  operation

Results:
  •The skill penetration rate has the positive relationship with skill migration rate
  
  •The skill penetration rate has the positive relationship with industry migration rate
  
  •Higher skill penetration rate != More opportunity to success
  
  •Lower skill penetration rate ≈ Lower opportunity to success

All sources used: 
https://www.migrationpolicy.org/research/contributions-high-skilled-immigrants
https://datacatalog.worldbank.org/dataset/world-bank-group-linkedin-dashboard-dataset
