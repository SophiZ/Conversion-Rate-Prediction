# Conversion-Rate-Prediction
Conversion rate, as one of the most important metrics for the E-Commerce platform, always plays a critical role in business. Increasing the conversion rate is the most cost-efficient and direct way to improve revenue. Here with the data from an online store, I performed exploratory data analysis and predictive modeling to provide actionable solutions for this store to boost conversion rate and increase revenue. <br>
## Goal:
To increase conversion rate (# conversions / total sessions)

## Data Description:
**country** : user country based on the IP address <br>
**age** : user age. Self-reported at sign-in step <br>
**new_user** : <br>
&nbsp; 1: the user created the account during this session <br>
&nbsp; 2: had already an account and simply came back to the site <br>
**source** : marketing channel source Ads: came to the site by clicking on an advertisement, seo or direct <br>
&nbsp; Ads: came to the site through ads <br>
&nbsp; Seo: came to the site by clicking on search results <br>
&nbsp; Direct: came to the site by directly typing the URL on the browser <br>
**total_pages_visited**: number of total pages visited during the session. This is a proxy for time spent on site and engagement during the session <br>
**converted**: this is our label <br>
&nbsp; 1 means they converted within the session <br>
&nbsp; 0 means they left without buying anything <br>

## Methodology:
1. Input Packages & Data <br>
2. Data Cleaning <br>
3. Exploratory Data Analysis <br>
4. Check Class Imbalance <br>
5. Modeling <br>
6. Result <br>
7. Summary <br>

### Note: 
This report is for self-learning purpose. The dataset is from the book "A Collection of Data Science Take-Home Challenges". Out of respect to the author of the original work, please go to https://datamasked.com/ for the original data.
