# Gene Expression Clustering Analysis

This repository contains a Google Colab notebook that we created as part of a group project for Sains Data Genom class. The notebook dives into gene expression data, using various clustering methods to uncover relationships between gene expression patterns across different samples. Our goal was to gain insights into genome characteristics and how they might relate to specific phenotypes.

## Overview

In this notebook, we explored several clustering techniques:

- Hierarchical Clustering
- K-Means Clustering
- Partitioning Around Medoids (PAM)

We also looked at how well these clusters held up by using silhouette scores. One interesting aspect of our analysis was the effect of selecting genes with high variance before clustering, which actually helped improve the clarity of our results.

## Key Findings

1. **Cluster Formation**:
   - Both samples and genes could be grouped into four main clusters.
   - We found a significant correlation between certain sample clusters and specific gene clusters, suggesting a strong link between genetic traits and sample responses.

2. **Example Insight**:
   - For instance, the samples GSM1290795 and GSM1290796 showed a high correlation with the gene 204952_at, meaning they had similar expression levels for this gene.

3. **Clustering Quality**:
   - Selecting high-variance genes before clustering improved the results, as shown by an increase in the average silhouette width for the optimal number of clusters.

## Conclusion

This clustering analysis offered us valuable insights into the genetic relationships among samples and genes. It highlighted the potential for understanding the factors influencing specific phenotypes better. Plus, it showed how important it is to carefully select genes when aiming for more accurate and interpretable clustering.
