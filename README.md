# Personalized-recommendations
This project suggests products to customers based on their purchase history. All files can be run on Google Colab.

Dataset:
The dataset was created using the Data_Generation.ipynb file. The csv has been downloaded.

Clustering:
There are two files that implements Customer Segmentation. Classification.ipynb implements a clustering algorithm that only accounts for product information, such as category, price, etc. In Cosine_recommendation.ipynb, the clustering algorithm also takes into account the date of purchase. This is the data that is used in the recommendation system. Both files use KPrototypes for clustering.
  - You may need to install kmodes. Simply uncomment the first cell to do so.

Recommendation:
The recommendation algorithm in Cosine_recommendation.ipynb uses cosine similarity. 
  - You may need to install kmodes and sklearn. Simply uncomment the first cell to do so.

The recommendation algorithm in SVD_recommendation.ipynb uses SVD.
  - You may need to install scikit-surprise, but this requires you to downgrade to numpy<2.
      - Uncomment the first three cells and run them
      - Restart the session before importing the libraries


