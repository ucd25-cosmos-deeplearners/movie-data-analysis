# Movie Data Clustering and Analysis

## What is this project?
This project is about analyzing a big dataset of movies and finding patterns using clustering. We used Python and Jupyter Notebook to explore the data, visualize it, and group similar movies together. The main goal was to see if movies can be grouped by their features like genre, popularity, ratings, and runtime, and then understand what makes each group special.

## What did we do?
- **Loaded the data:** We started by loading a CSV file with lots of movies and their features (like genres, popularity, vote average, runtime, etc).
- **Cleaned the data:** We removed any duplicate movies to make sure the analysis was accurate.
- **Explored the data (EDA):**
  - Made histograms to see the distribution of things like popularity and ratings.
  - Used boxplots to spot outliers and see the spread of the data.
  - Made scatterplots and pairplots to look for relationships between features.
- **Dimensionality Reduction:**
  - Used **PCA (Principal Component Analysis)** to reduce all the features to just 2, so we could plot the movies on a 2D graph.
  - Used **t-SNE** to do the same thing, but t-SNE is better at showing clusters.
- **Clustering:**
  - Used **KMeans** to group the movies into 4 clusters, both on the PCA and t-SNE projections.
  - For each cluster, we checked which genres were most common, and calculated the average popularity, rating, and runtime.
- **Visualization:**
  - Plotted the clusters on scatter plots to see how they look.
  - Made bar graphs to show the percentage of each genre in every cluster, with different colors for each genre (like blue for Action, brown for Sci-Fi, etc).

## What did we find?
- Each cluster had its own mix of genres. For example, some clusters had more Action or Sci-Fi movies, while others had more Drama or Romance.
- The clusters also had different average popularity, ratings, and runtimes.
- Using PCA and t-SNE made it much easier to see the groups and understand the data.
