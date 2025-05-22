# Clustering-Alcoholic-Beverages
In this project, we will be using an unlabelled dataset from DataCamp to find patterns, clusters, and relationships that exist in the alcohol dataset. The methods we will be using are t-SNE, K-Means, and other data preprocessing methods.

# What is K-Means and t-SNE?
K-Means and t-SNE are both unsupervised learning techniques that have different purposes but can also be used together. K-Means is a clustering algorithm that groups data into *k* number of clusters. We will also use t-SNE, which is a dimension reduction which aims to maintain local structures for plotting purposes. The two techniques can be used together for clustering and plotting, which will be seen.

# Scaling the Data
The dataset consisted of 13 columns regarding the percentage or amount of certain elements a drink/beverage contained. Many of these columns were not on the same scale(percentage vs amount), so scaling the data was necessary so all features contribute to the model.

# Clustering Data 
To figure out how many clusters to use, we can fit multiple K-Means models with different numbers of clusters(1-10) to the scaled data. We will then find the inertia value for each model, which is a measure of how well the model clusters that data. We want to find a model with both a low inertia and a low cluster amount. We will then fit the appropriate model and predict labels. 

# t-SNE Transformation
For plotting methods, we applied a t-SNE model to the scaled data to reduce dimensionality. Using seaborn, we will apply the prediction labels to show the scatter and how they relate to one another.

# Further Exploration
Lastly, grouping the data by label to find how features differ is very important. We then plotted those findings and found out that drinks in label 2 have higher levels of Proline and Magnesium, and drinks in label 0 have lower amounts of alcohol and color intensity. 

# Conclusion
Using unsupervised Learning, we can make inferences about groups of unlabeled data and make observations on those clusters using many different types of techniques.
