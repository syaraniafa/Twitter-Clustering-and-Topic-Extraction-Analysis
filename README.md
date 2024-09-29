# Twitter Clustering and Topic Extraction Analysis on BSI Ransomware Case

## Case Study - Final Examination
In 2023, Bank Syariah Indonesia (BSI) faced a ransomware attack, disrupting its national operations. This incident drew significant attention on social media, especially Twitter (X), where users shared their opinions and responses. In this project, the goal is to analyze tweets related to the BSI ransomware incident using clustering and topic extraction techniques. The results will provide insights into what users discussed and how they responded to the event.

## Project Overview
This project aims to analyze and model Twitter (X) data related to the 2023 BSI ransomware case. Two approaches are employed: clustering and topic extraction. We compare the results of these methods to uncover the main themes and personas of Twitter users. Key steps include experimenting with different cluster values, conducting persona analysis for clusters and topics, and comparing the insights gained from both techniques.

## Steps Involved
### Part 1: Clustering Analysis
1. **Data Collection and Preprocessing**
Twitter (X) data is collected using Twitter's API (or web scraping). Each tweet is preprocessed, including:
    - Removal of URLs, mentions, and special characters
    - Tokenization and stopword removal
    - Text vectorization using TF-IDF or other embedding techniques (e.g., Word2Vec, BERT).
2. **Clustering Model**
The tweets are clustered using a suitable algorithm, such as **K-Means Clustering**. Several values for the number of clusters (k) are experimented with, and the optimal number of clusters is determined by comparing **Silhouette Scores** for different k values.
3. **Cluster Evaluation**
The clusters are evaluated based on the silhouette score. The optimal number of clusters is chosen by maximizing the silhouette score, which measures how similar each tweet is to its own cluster compared to others.
4. **Persona Analysis for Clusters**
Once the clusters are established, persona analysis is performed. The personas represent the dominant characteristics of each cluster, which could include common topics, sentiment, or specific language patterns used by users in each cluster.

### Part 2: Topic Extraction
1. **Topic Extraction Model**
To compare with clustering, a **Topic Extraction** method, such as **Latent Dirichlet Allocation (LDA)**, is employed. This method identifies the underlying topics in the tweet dataset. Each tweet is then assigned a set of topics with associated probabilities.
2. **Persona Analysis for Topics**
After extracting the topics, persona analysis is conducted for each topic. This analysis identifies the key themes and patterns in user discussions within each topic, similar to how personas were analyzed in the clustering phase.
3. **Comparison of Clustering vs. Topic Extraction**
The results of clustering and topic extraction are compared to identify any common patterns or discrepancies between the two approaches. Key comparisons are drawn between:
    - The number of clusters vs. topics.
    - The similarities and differences in user personas identified by both methods.
  
## Results and Analysis
**Clustering Results:**
- Silhouette Scores: A comparison of silhouette scores for different cluster values (k) will be provided, justifying the optimal number of clusters.
- Cluster Personas: A detailed breakdown of the personas for each cluster, including key themes, language patterns, and sentiments, will be presented.

**Topic Extraction Results:**
  - Topic Breakdown: Each topic will be described with its most significant words and a brief interpretation of what the topic represents.
  - Topic Personas: Similar to clusters, personas for each topic will be analyzed based on the underlying user discussions.

**Comparative Insights:**
A side-by-side comparison of the results from clustering and topic extraction will be made. Interesting insights, such as overlapping themes, differences in user personas, and unique findings from each method, will be highlighted.

## Conclusion
This project demonstrates the use of both clustering and topic extraction techniques to analyze Twitter (X) data related to the BSI ransomware case. The comparison of the two methods provides insights into how users responded to the incident and what was predominantly discussed on the platform.
