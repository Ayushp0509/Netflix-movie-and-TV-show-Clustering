# **NETFLIX MOVIES AND TV SHOWS CLUSTERING**

## **PROJECT OVERVIEW**

The goal of this project is to analyze the Netflix Dataset of movies and TV shows until 2019, sourced from the third-party search engine Flixable. The aim is to cluster the content using Natural Language Processing (NLP) techniques, contributing to improving user experience and preventing subscriber churn on Netflix, the world's largest online streaming service with over 220 million subscribers. Additionally, the dataset will be explored to uncover new insights and trends in the streaming entertainment industry.

## **DATASET**

The dataset used for this analysis is the [Netflix Movies and TV Shows Dataset](https://drive.google.com/file/d/1tTe_ZNRN5WZ8JTUOej5-v4WzE6ymoeaS/view?usp=drive_link). It provides comprehensive information on Netflix content until 2019.

## **PROJECT WORKFLOW**

1. **HANDLING MISSING VALUES:**
   - Dealt with null values/missing values in the dataset.

2. **NESTED COLUMNS HANDLING:**
   - Handled nested columns like director, cast, listed_in, and country for clearer visualization and analysis.

3. **RATING BINNING:**
   - Binned the rating attribute into appropriate categories, such as adult, children's, family-friendly, and not rated content.

4. **EXPLORATORY DATA ANALYSIS (EDA):**
   - Conducted EDA on various attributes to gain valuable insights for preventing subscriber churn.

5. **CLUSTER CREATION:**
   - Created clusters using attributes like director, cast, country, genre, rating, and description.
   - Tokenized, preprocessed, and vectorized using TFIDF (Term Frequency-Inverse Document Frequency) vectorizer.

6. **DIMENSIONALITY REDUCTION:**
   - Reduced the dimensionality of the dataset using PCA to improve performance.

7. **CLUSTERING ALGORITHMS:**
   - Utilized K-Means Clustering and Agglomerative Hierarchical Clustering algorithms.
   - Determined optimal cluster numbers using methods such as the Elbow method, Silhouette score, Dendrogram, etc.

## **CONCLUSIONS**

### **FROM EDA**
- Movies constitute about two-thirds of Netflix content, with TV shows making up the rest.
- Adult and teen categories dominate, with family-friendly content more common in TV shows.
- Indian actors are prevalent in movies, while TV shows lack popular Indian actors.
- The U.S. is the largest producer on Netflix, followed by India, Japan, and South Korea.
- International movies, drama, and comedy are popular genres.
- The number of TV shows added has increased since 2018, while movies have decreased.
- October, November, and December are peak months for adding TV shows.

### **FROM ML MODEL**
- Implemented K-Means and Agglomerative Hierarchical Clustering.
- Optimal clusters: 4 for K-Means and 2 for Agglomerative Hierarchical Clustering.
- Silhouette Score chosen for evaluation due to its interpretability and sensitivity.
  

