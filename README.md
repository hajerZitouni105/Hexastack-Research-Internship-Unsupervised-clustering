# Comparative Analysis of Unsupervised Text Clustering Algorithms and NLP Preprocessing Techniques

## Project Overview
This project explores the effectiveness of various unsupervised clustering algorithms and NLP preprocessing techniques for text clustering. Conducted as part of a summer research internship, the objective was to identify optimal combinations of preprocessing methods and clustering models to achieve high clustering accuracy and meaningful groupings of textual data. 

## Research Methodology

1. **Dataset Description**: 
   - A detailed examination of the dataset characteristics, including its size, structure, and nature of text entries.

2. **NLP Preprocessing Techniques**: 
   - Various preprocessing techniques were applied to the dataset, such as tokenization, stemming, lemmatization, stop-word removal, and vectorization, to prepare the text for effective clustering.

3. **Clustering Algorithms**: 
   - Multiple clustering algorithms were tested, each chosen for its suitability in unsupervised text clustering:
     - **K-Means**: Widely used for its simplicity and efficiency.
     - **Hierarchical Clustering**: Provides a tree-like structure of clusters, ideal for interpretability.
     - **DBSCAN**: Density-based clustering, effective for identifying noise and outliers.
     - **Gaussian Mixture Model (GMM)**: Probabilistic approach for modeling the data distribution in clusters.

4. **Performance Evaluation**: 
   - Clustering quality was assessed using metrics such as Silhouette Score, Davies-Bouldin Index, and Homogeneity Score. These metrics provided insights into cluster cohesion, separation, and consistency.

## Experimental Results

1. **Comparison of Clustering Algorithm Performance**: 
   - Detailed analysis and performance comparison for each clustering algorithm, with an emphasis on their effectiveness in grouping similar texts.

2. **Impact of Preprocessing on Clustering Results**: 
   - Evaluation of how different NLP preprocessing techniques influenced the clustering results, including the identification of the most effective preprocessing steps.

3. **Qualitative Analysis of Clusters**: 
   - Examination of cluster content to verify the interpretability and relevance of clustered text groups.

4. **Optimal Configurations**: 
   - Identification of the best-performing combinations of preprocessing techniques and clustering algorithms, such as using Sentence Transformers with Agglomerative Clustering or K-Means.

## Discussion

1. **Interpretation of Results**:
   - Our findings indicate that Sentence Transformers, combined with Agglomerative Clustering and K-Means, provide the most accurate clustering results, suggesting these methods are well-suited for unsupervised text clustering tasks.

2. **Limitations and Future Directions**:
   - The study acknowledges potential limitations, such as dataset-specific characteristics that may influence results. Future research could explore alternative algorithms and preprocessing techniques to further improve clustering performance and robustness.

3. **Potential Applications**:
   - The findings offer practical insights for real-world applications of unsupervised text processing, such as document categorization, topic modeling, and content recommendation systems.

## Conclusion

This research project contributes to the field of unsupervised text clustering by highlighting the impact of preprocessing choices on clustering accuracy. The methodology and results provide a framework for applying clustering models to diverse, unlabelled text datasets.

---

