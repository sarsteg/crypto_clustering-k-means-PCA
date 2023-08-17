# Applying Unsupervised Learning

I undertook an engaging project to utilize Python and unsupervised learning techniques to predict the impact of 24-hour and 7-day price changes on cryptocurrencies. This project aimed to uncover patterns within the cryptocurrency market and demonstrate the potential of unsupervised learning for predictive analysis. Through this endeavor, I showcased my proficiency in data manipulation, normalization, dimensionality reduction, and clustering algorithms.

The project involved the following key steps:

1. **Repository Setup:** I established a dedicated repository named "CryptoClustering" to house the project code and resources, ensuring a structured and organized workflow.
2. **Data Exploration and Preprocessing:** The analysis commenced by loading the cryptocurrency market data from the provided CSV file into a DataFrame. I examined the data's summary statistics and visualized its distribution to gain an understanding of its structure and characteristics.
3. **Data Normalization:** Utilizing the scikit-learn library's StandardScaler module, I normalized the data to bring it to a consistent scale. This step was crucial for ensuring accurate and meaningful clustering.
4. **K-Means Clustering:** Employing the K-means clustering algorithm, I embarked on finding the optimal number of clusters (k) using the elbow method. By computing the inertia values for different k values, I visually identified the point of inflection on an elbow curve, determining the most suitable k value.
5. **Clustering Analysis:** With the optimal k value determined, I proceeded to cluster the cryptocurrencies based on the original scaled data. I utilized the K-means model to predict clusters and visualized the results using scatter plots with labeled data points. This provided valuable insights into the cryptocurrency groups.
6. **Principal Component Analysis (PCA):** To enhance the clustering process, I performed PCA on the original scaled data, reducing its dimensions to three principal components. I calculated the explained variance of each component, highlighting their significance in capturing the data's variability.
7. **Enhanced Clustering with PCA:** Leveraging PCA-reduced data, I repeated the clustering process using K-means to find the best k value for this reduced feature set. This enabled a comparison between clustering outcomes using both original and reduced data.
8. **Impact of Dimensionality Reduction:** Through a scatter plot, I visually demonstrated the impact of using fewer features (principal components) on the clustering process. This step provided a clear understanding of how dimensionality reduction affected clustering outcomes.

Throughout this project, I harnessed my expertise in Python programming, data preprocessing, normalization techniques, K-means clustering, principal component analysis, and data visualization using libraries like scikit-learn and hvPlot. The project's success lies in its ability to showcase the power of unsupervised learning in extracting valuable insights from complex cryptocurrency data, effectively highlighting trends and patterns that can inform investment decisions and strategies.
