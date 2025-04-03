# Personalized-recommendations
This project suggests products to customers based on their purchase history. All files can be run on Google Colab.

How to Run:
All files are uploaded as Python Notebooks. The links to the Google Colabs are linked below.
1. If you want to create your own dataset, use the link to Data_Generation.ipynb and run all cells
     - The dataset created will be used in the upcoming steps
     - Link: https://colab.research.google.com/drive/13odxIDVgcRQ7NJ8WbAKZvgp7BKq72JtJ?usp=sharing
  
   If you want to use the dataset I created, download the purchase_data.csv in the Dataset folder

2. To view the clustering results and stats, use the link to Clustering_Final.ipynb.
     - Upload the dataset from Step 1
     - Run all the cells
     - This will output a csv file with the clustering results called customer_segmentation.csv
     - Link: https://colab.research.google.com/drive/1an9UDp9DJBBYu50EwHO7rji1HCm3Z1DQ?usp=sharing
  
3. To run the recommendations algorithm, use the link to Cosine_sim_recommendation_Final.ipynb.
     - Upload the dataset from Step 1
     - Run all the cells
     - To download the recommendations for all customers, uncomment the last cell and run it. It will output a csv file called customer_recommendations.csv
     - Link: https://colab.research.google.com/drive/1JXN7Hxv4dXAAYYe8VrhlpldmciXolb-W?usp=sharing
