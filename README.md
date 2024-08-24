# Beer Reviews Excercise <br>
<br>
This is the exploratory analysis of beer_reviews dataset by BeerAdvocate from data.world. The main goal of this analysis is to answer the below questions: <br>
- Which brewery produces the strongest beers by abv? <br>
- If you had to pick 3 beers to recommend to someone, how would you approach the problem? <br>
- What are the factors that impacts the quality of beer the most? <br>
- I enjoy a beer which aroma and appearance matches the beer style. What beer should I buy?<br>
<br>
To answer the questions, I have split the exercise into 2 parts:<br>
<br>
<br>

***PART 1: DATASET EXPLORATION*** - including:<br>
<br>
1. Importing required libraries
2. Importing the provided dataset from data.world into a dataframe
3. Reviewing the data
<br>
<br>

***PART 2: ANSWERING THE QUESTIONS*** <br>
<br>
Here are my answers to the questions:

**QUESTION 1: Which brewery produces the strongest beers by abv?**

<br>

![image](https://github.com/user-attachments/assets/a3f1cbf9-4994-4852-ab0c-25c4d3cbbc9a)

Taking into consideration mean values of beer strenght (as beer_abv) for all beers produced in the given brewery, according to the dataset, the strongest beers are produced in brewery Schorschbräu. This brewery also produces the strongest beers included in the dataset:

- Schorschbräu Schorschbock 57% and
- Schorschbräu Schorschbock 43%

<br>

**QUESTION 2: If you had to pick 3 beers to recommend to someone, how would you approach the problem?** <br>
<br>

In order to pick 3 beers to recommend to someone, I have identified the beers that:

- are popular (have many reviews),
- provide best value for parameters that are important for me (overall review, taste and aroma),
- are weakest possible.
<br>

![image](https://github.com/user-attachments/assets/c2b0c642-de03-4ddd-af7f-37a1cecf38a2)


Based on the results, there is a list of beers all rated:

- 5 overall
- 5 for taste
- 5 for aroma
- with strength below 4.5
<br>
I would choose the beers with highest amount of reviews, as it means the highest number of people agreed on their qualities, making them a safe recommendation. The recommended beers would be:

- Guinness Draught
- Yuengling Traditional Lager
- Bud Light
<br>

**QUESTION 3: What are the factors that impacts the quality of beer the most?** <br>

<br>

![image](https://github.com/user-attachments/assets/e3ffead8-51e8-4eee-acf6-cf934bd9a1cc)
![image](https://github.com/user-attachments/assets/b97ba20f-47e8-428a-8046-053a3c8255c6)
![image](https://github.com/user-attachments/assets/81a53b56-ea1a-4f92-b9ff-0f95da0186d4)

Summary of the correlation coefficient between overall reviews and other parameters:<br>
![image](https://github.com/user-attachments/assets/64d45aa4-d494-4be8-b38f-0fa168449596)

Based on the correlation between overall reviews and other parameters, we see that there are a few factors affecting the overall perception of a beer:

- taste and palate have the highest impact, with very strong correlation,
- aroma and appearance also show strong correlation,
- and there is no or very weak correlation with the beer strength, which means, that the parameter beer_abv doesn't impart the overall perception of the beer. <br>

To sum up, all 4 factors (taste, palate, aroma and appearance) greatly affect the overall perception of the beer, but the 3 factors, that affect it the most are (in order):

- taste,
- palate and
- aroma.

<br>

**QUESTION 4: I enjoy a beer which aroma and appearance matches the beer style. What beer should I buy?** <br>

<br>

![image](https://github.com/user-attachments/assets/a2c63a78-5117-44d2-9016-146a90b05de0)

Based on the difference of aroma and appearance from the mean values per beer style, the beer that best matches its style is **Aiko from Rinkuškiai Alaus Darykloje brewery**. If you're into Euro Strong Lager beer styles, that's the beer you definetly should buy.
