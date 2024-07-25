<h1 align="center">Zomato Restaurant Clustering And Sentiment Analysis</h1>

![20 zomato_1-sixteen_nine](https://github.com/user-attachments/assets/44bdcba4-ee3d-44c2-9b3f-fdb905ec77ee)




**Project Type: Unsupervised Machine Learning**

**Project Overview**

This project dives deep into Zomato's Indian restaurant landscape, using unsupervised machine learning to uncover hidden patterns and insights. We aimed to understand not only what customers are saying about restaurants, but also to group restaurants into distinct categories based on their characteristics. By analyzing cuisines, costs, ratings, and customer sentiments, we seek to provide valuable recommendations for both Zomato and restaurant owners.

**Key Findings and Goals**

* **Popular Cuisines Dominate:**  North Indian and Chinese cuisines reign supreme, being the most frequently offered and highly reviewed. This underscores their popularity among Indian diners.
* **Mid-Range Restaurants Thrive:** Most restaurants fall into the medium to low price range, indicating a preference for affordable dining options. However, a niche for high-priced, fine-dining experiences also exists.
* **Hygiene and Buzzwords Matter:** Zomato tags like "Food Hygiene Rated" and "Trending this week" were commonly associated with popular restaurants, emphasizing the importance of hygiene and current trends.
* **Positive Sentiment Prevails (with Caveats):** Overall sentiment towards restaurants is positive, but a significant portion of negative reviews highlights areas for improvement, particularly in taste, service, and hygiene.
* **Critic Influence:** Individual critics like Satwinder Singh hold substantial influence, with their reviews carrying weight due to their large follower base.

**Technical Approach**

1. **Data Preparation:**
   * **Cleaning:** Handled missing values, outliers, and inconsistencies in the dataset.
   * **Feature Engineering:** Extracted features like the number of cuisines offered and categorized restaurant cost into tiers (low, medium, high).
   * **Encoding:** Transformed categorical data (cuisines) into a numerical format for clustering.

2. **Exploratory Data Analysis (EDA):**
   * **Visualizations:** Created pie charts, histograms, bar charts, word clouds, and more to understand the distribution of cuisines, costs, ratings, and collection tags.
   * **Correlations:** Analyzed relationships between variables (e.g., cost vs. rating) to uncover potential patterns.
   * **Time Analysis:** Examined how ratings vary throughout the day.

3. **Clustering (K-means and Hierarchical):**
   * **Dimensionality Reduction (PCA):** Reduced the number of features to improve clustering efficiency.
   * **Optimal Cluster Selection:** Used elbow curves and silhouette analysis to determine the best number of clusters.
   * **Cluster Interpretation:**  Identified and labeled distinct clusters based on restaurant characteristics (e.g., "Street Flavor Hub," "Global Cuisine Delights").

4. **Topic Modeling (LDA):**
   * **Topic Extraction:**  Uncovered hidden themes in customer reviews (e.g., "Entertainment and Atmosphere," "Bad Food Experience").
   * **Topic Visualization:** Presented top words within each topic for easy interpretation.

5. **Sentiment Analysis:**
   * **Classification:** Labeled reviews as positive, negative, or neutral.
   * **Polarity and Subjectivity:** Measured the strength and emotional intensity of sentiments.
   * **Word Clouds:** Visualized most frequent positive and negative words to pinpoint key factors influencing sentiment.


**Recommendations**

* **Zomato:**
   * Highlight hygienic practices and trending restaurants to attract users.
   * Develop a personalized recommendation system based on our cluster analysis and user preferences.
   * Consider incorporating sentiment analysis into your platform to quickly identify restaurants needing improvement.
* **Restaurant Owners:**
   * Focus on menu diversity within the popular North Indian and Chinese cuisines.
   * Ensure consistent quality and hygiene standards to maintain positive customer sentiment.
   * Pay attention to feedback in reviews, especially regarding negative aspects.


