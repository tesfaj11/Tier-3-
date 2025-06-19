# Tier-3-
Tier_3_App_Ratings_Analysis.ipynb 
# App Ratings Case Study – Tier 3

## Project Overview
For this project, I compared app ratings from the Apple App Store and Google Play Store to help decide which one should be integrated into a new operating system. I used app ratings as a way to measure app quality, and my goal was to figure out if there was a real difference between the two platforms.

## Objective
The main question I wanted to answer was: **Is there a significant difference in app ratings between Apple and Google Play?** If one clearly had better ratings, that’s the store I’d choose. If not, I’d just flip a coin.

## What I Did
- Cleaned and prepared app rating data from both platforms
- Did some exploratory analysis to understand how the ratings are distributed
- Ran a statistical test (two-sample t-test) to compare the average ratings

## What I Found
- Google Play apps had a higher average rating (~4.19) than Apple apps (~3.53)
- Google ratings were more consistent overall, while Apple had a lot more low-rated apps
- The test showed a p-value close to zero, which means the difference is **statistically significant**

## Final Decision
Based on the data, I recommend going with the **Google Play Store**. The apps there seem to be rated higher overall, and the difference is unlikely to be due to random chance.

## Files
- `Tier_3_App_Ratings_Analysis.ipynb` – My full notebook with all the code, analysis, charts, and conclusion

## Skills Used
- Data cleaning with pandas
- Visualizations with seaborn and matplotlib
- Hypothesis testing (two-sample t-test)
- Drawing conclusions based on statistics
