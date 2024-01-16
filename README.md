# LA-concert-local-economy

**Project Title:** "Yelping to the Rythm"

**Objective:** For this project, we decided to investigate whether there is a correlation between a prominent artist performing in Los Angeles during a specific week and an increase in Yelp reviews. We are interested in studying this relationship to measure the influence of celebrities on local economic fluctuations. Based on research, mega artists such as Beyonce, have even been blamed for causing inflation in the countries they are touring in (for example: Sweden).

As part of my first semester at USC, I conducted this study as the final project for a Business Analytics class with 7 other students. In this project, we scraped open-source data and information online (Live Nation, etc) to collect data on mainstream music concerts in Los Angeles from 2014-2017. 

We performed a **t-test**, **linear regression**, and **multilinear regression** analyses to explore the correlation between music concerts and the culinary economy in Los Angeles.

---

**Data Source:**
- Yelp reviews from restaurants across downtown LA (provided by professor Mohammed Alyakoob from USC)
- Concert dates in LA from 204-2017 (independent sourced from open sources)

<img src="https://github.com/rsoetirto/LA-concert-local-economy/assets/109045573/67f8b98d-f699-46e2-adcc-fc01e4cb6d90" width="300" height="300" />
<img src="https://github.com/rsoetirto/LA-concert-local-economy/assets/109045573/322c455b-f4ee-4fa6-bbd0-833303cb2f9e" width="450" height="450" />

<br> 
</br>

**Preview of cleaned dataset:**
![Screenshot 2024-01-16 at 11 35 45 AM](https://github.com/rsoetirto/LA-concert-local-economy/assets/109045573/f777a6e9-9177-4c4d-8240-4a712d06b4ff)

---
**Testing**
As specified above, our team conducted a number of statistical tests to support our objective. We tested for the difference in the average number of Yelp reviews for weeks when there is a concert recorded versus when there isn’t, among all the 208 weeks spanning four years that we collected data points on.

Our hypotheses are:
**Ho:** There is no difference between the number of Yelp reviews in the two groups.
**Ha:** There is a difference between the number of Yelp reviews in the two groups.

This is an excerpt of some our visualizations for this study:
![Screenshot 2024-01-16 at 11 45 46 AM](https://github.com/rsoetirto/LA-concert-local-economy/assets/109045573/96821cc9-36d2-4c12-875f-24534e5c263a)

---

**Conclusion:**

Read the full executive summary of the project [here](https://docs.google.com/document/d/1GjeSxCmCnB5Bv4DZV1L6JqBfWuT9SUgrA5_rUiTnsBs/edit).

According to our study, the actual difference between the two groups is that weeks with a concert have 1.3 more reviews on average than weeks without a concert. However, this result is not statistically significant, as we could observe from a p-value of 0.96. 

Based on the results, we conclude that we failed to reject the null hypothesis that there is no difference between the number of Yelp reviews in the two groups. We cannot confirm that concerts increase the number of Yelp reviews submitted, and we could not completely isolate as many confounding variables as possible to prove that there is a relationship between our dependent variable and independent variables. Although, based on our model, we can logically assume that the number of reviews increases with the presence of concerts happening that week, we cannot completely and safely assume this same-case scenario in real-life situations where more variables and scenarios exist.













