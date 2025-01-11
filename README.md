# CryptoClustering
Repository for Module 11 Homework.

**Questions/Answers in Homework**
- Question 1 (Best k using orig. scaled df): What is the best value for k? **4.**
- Question 2 (Optimize clusters with PCA): What is the total explained variance of the three principal components? **89.5%.**
- Question 3 (Best k using PCA): What is the best value for k? **4.**
- Question 4 (Best k using PCA): Does it differ from the best k value found using the original data? **No. It is the same.**
- Question 5:

***PCA1:***

**price_change_percentage_1y** has the strongest positive influence, suggesting it contributes significantly to the first principal component.(0.594468)

**price_change_percentage_24h** has the strongest negative influence, meaning shorter-term price changes inversely impact PCA1. (-0.416728)

***PCA2:***

**price_change_percentage_30d** has the strongest positive influence, indicating medium-term price changes are a key factor in PCA2. (0.562182)

**price_change_percentage_1y** contributes negatively but weakly compared to PCA1. (-0.150789)

***PCA3:***

**price_change_percentage_7d** has a dominant positive influence, highlighting the importance of short-term weekly changes for PCA3. (0.787670)

**price_change_percentage_60d** contributes negatively to PCA3, suggesting opposing trends in medium-term changes. (-0.361377)
