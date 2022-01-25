# Recommendation-Engines-for-the-IBM-Watson-Studio-Platform

## Summary
IBM has an online data science community where members can post tutorials, notebooks, articles, and datasets. In this project, I built various recommendation engines, 
based on user behavior and social network for the IBM Watson Studio's data platform, to surface content most likely to be relevant to a user.

## Files 

### data

#### articles_community.csv
<img src="https://user-images.githubusercontent.com/39535338/150942605-5fcea3a2-f7e9-47a5-8181-e36ff4293bbd.PNG" alt="drawing" width="800"/>

#### user-item-interactions.csv
<img src="https://user-images.githubusercontent.com/39535338/150942569-ddc2b40e-1909-4804-a6c3-98a2181a5d59.PNG" alt="drawing" width="800"/>

### Recommendations_with_IBM.ipynb
- This notebook contains the Exploratory Data Analysis as well as the code used to build different methods for making recommendations for different situations such as:
  - <b>Rank Based Recommendations:</b> In this dataset we only know that a user has interacted with an article. In these cases, the popularity of an article can really only be based on how often an article was interacted with.
  - <b>User-User Based Collaborative Filtering:</b> recommending articles based on the most similar users to the target user,
  - <b> Matrix Factorization:</b> Splitting the data into training and test sets and tunning the number of latent features

### user_item_matrix.p
a pickle file with a matrix of the user_ids and articles that have interacted with
<img src="https://user-images.githubusercontent.com/39535338/150944797-8a18c5ce-7f31-4c28-8632-cc3b8365b97a.PNG" alt="drawing" width="800"/>
