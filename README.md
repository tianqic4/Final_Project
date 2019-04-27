# Final_Project
## Title: 

### Analysis of the factors affecting the trend of talents in the world and the success rate of individual immigration

## Team members:
Tianqi Chen
Yanan Shen



# Part 1 

## Purpose:

The influencing factors of immigration have been controversial. Thus, we are curious about whether the fluctuation of the Employment rate will affect the net migration rate. This section we analyzed the correlation between Net Migration Rate and Employment Growth Rate and the trend of 2015 to 2018 from six industry classifications. Moreover, a comparison is made between developing country - China and developed country - the United States.

###### In this part, we will answer the following questions:

Does the Industry Net Migration Rate will be affected by the Industry Employment Growth Rate?

Is the trend of Industry Net Immigration Rate similar between China and the United States? (2015 - 2018)

Is the trend of Industry Employment Growth Rate similar between China and the United States? (2015 - 2018)

## Hypotheses: 
As the Employment Growth Rate increases, the Net Immigration Rate of the industry will also rise. (2015 - 2018)

The trend of Industry Net Immigration Rate is not similar between China and the United States. (2015 - 2018)

The trend of Industry Employment Growth Rate is similar between China and the United States.  (2015 - 2018)

## Design reasoning: 

##### 1.Data preparation and Data cleaning 
We sorted out the data for each dataset separately. 
We merged 2 datasets (Employment Growth from Industry Transition
& Industry Migration) and removed major errors and inconsistencies. 
##### 2.Data processing
We unified data form which can facilitate subsequent analysis.
We Found the different industry names, which were included in each industry classification and got industry data from the same industry classification but under different countries (China & United States) from 2015 to 2018.
##### 3.Creating bar graph
Comparison of Industry Net Migration Rate of China in 2015 and 2018
Comparison of Industry Net Migration Rate of United States in 2015 and 2018
Comparison of Industry Employment Growth Rate of China in 2015 and 2018
Comparison of Industry Employment Growth Rate of United States in 2015 and 2018

## Results:

We selected two countries for comparison, China and the United States. China is a developing country and a non-immigrant country. However, The United States is a developed country, and its immigration policy is more lenient than that of China. It belongs to an immigrant country and has a diverse culture.
For the first hypothesis, we found that the net industry immigration rate and the industry employment growth rate  in the U.S. are positively correlated between 2015 and 2018, in addition to two industry classification (Arts, entertainment and recreation and Manufacturing).  However, China has no obvious correlation.
For the second hypothesis, the trend of Industry Net Immigration Rate is similar between China and the United States (2015 - 2018), in addition to manufacturing. 
For the third hypothesis, the trend of Industry Employment Growth Rate is basically opposite between China and the United States (2015 - 2018), in addition to Financial and insurance activities. 

## Analytical Summary of our findings:
For the correlation between Industry Net Immigration Rate and Industry Employment Growth Rate: 
We found that there is a significant difference in the correlation between countries, and we need to consider whether the country is a large immigrant country or whether the immigration policy is flexible.

From 2015 to 2018, the net migration rate of nearly all industries is a       downward trend in the United States. The reason may be due to the U.S. immigration policy has tightened in recent years. 

For the six industry classifications, the employment growth rate of nearly four industries in China is negative both in 2015 and in 2018. The four industry classifications are:  Information and communication, Manufacturing, Mining and quarrying  and Professional scientific and technical activities. 
We found that there is an interesting phenomenon: 
In 2015, the employment growth rate of the Information and Communication industry was far ahead of other industries. The growth rate even exceeds 25 percent. However, in 2018, the employment growth rate of the industry is the lowest in all industries, and it even becomes negative. 

Information and Communication industry classification includes the following industry:  

                     Computer Hardware
                     Computer Software
                   Computer Networking
                              Internet
                        Semiconductors
                    Telecommunications
               Motion Pictures & Film
                      Broadcast Media
                           Newspapers
                           Publishing
    Information Technology & Services
                       Computer Games
                         Online Media
          Computer & Network Security
                             Wireless
                     Media Production


# Part 2 

## Purpose:

For this part, we mainly focus on how skill penetration rate impacts the net migration rate of skill migration and industry
migration from 2015 to 2018.The target is the whole world.

## Hypotheses:

Skill peneration rate has positive correlation relationship with net migration of skill migration and industry migration

## Design reasoning:  
##### 1.Merge 4 dataset (industry migration-- industry needs skills--skill migration--skill penetration rate)
  Be more convenient to establish the relationship between the skill penetration rate and net migration rate of skill and
  industry migration.

##### 2.Calculate the difference 
  This step is to calculate the difference between the 2015 net per 10K  and 2018 net per 10K  and the difference between the
  2015 skill penetration rate and 2018 skill penetration rate to know the net migration increase or decrease.
  Net per 10k: with different industry section and name, the net migration rate of skill migration.

##### 3.Drawing plot by using calculated difference value

##### 4.Find the oulier of skill penetration rate difference 
  This step is based on the third step. The outlier could be the further demonstration of hypothesis 
  
## Analytical Summary of our findings:

  ##### Skill migration line chart and pie chart:
  positive correlation relationship
  Abnormal Value: soft skills (like leadership, problem solving). Although it is more and more important and needed by each
  industry, it still not belong to thigh-skilled immigration.
  The pie chart demonstrate although the difference trend between skill penetration rate is positive correlated, the total
  number of people who could success skilled migration is not have the positive correlated as the trend. It still have the
  situation that although the skill penetration is increase, the number of the skilled migration is decreasing
 
  ##### Industry migration line chart and pie chat:
  positive correlation relationship 
  Abnormal industry section is professional scientific and technical activities. We could find that the skill presentation is
  high but the net 10k is low explained by upper outlier scatter plot

  ##### Outlier:
  The upper outlier is calculated by skill penetration rate. we also could see that the net 10 k for this value is lower than
  0 which means the number people who belongs to this category is reducing but the this skill is increasing. This could 
  totally explained why profession industry has high skill penetration but low net migration rate.
  For the lower outlier, it is totally different, we can see that most point is below 0 which means the skill rate is lower 
  and the net migration is lower which is the positive relationship,especially people who have skill on manufacturing 
  operation

## Results:
  
  •The skill penetration rate has the positive relationship with skill migration rate
  
  •The skill penetration rate has the positive relationship with industry migration rate
  
  •Higher skill penetration rate != More opportunity to successfully immigrate
  
  •Lower skill penetration rate ≈ Lower opportunity to successfully immigrate 

## All sources used: 
https://www.migrationpolicy.org/research/contributions-high-skilled-immigrants
https://datacatalog.worldbank.org/dataset/world-bank-group-linkedin-dashboard-dataset


## Our Pre-recorded Video link:

https://youtu.be/o5DSpW1s1K4
