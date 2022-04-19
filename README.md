# Cryptocurrencies
## **Overview**
From our research to understand what unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principal components using PCA.  We will use unsupervised learning to group the cryptocurrencies, Martha decided on a clustering algorithm. 
We will use data visualizations to share the findings.

## **Resources**
Software: Python 3.10.1, Visual Studio Code 1.63.2, Pandas 1.2.4, Jupyter Notebook 6.4.8
crypto_cata.csv

## **Results**
### *Preprocessing the Data for PCA*
- Imported DataFrame
<img width="632" alt="Imported DF" src="https://user-images.githubusercontent.com/91889241/163896897-60a43128-db81-481c-b14b-8b699e1830fe.png">

- Standardized DataFrame using StandardScaler
<img width="295" alt="Screen Shot 2022-04-18 at 7 25 00 PM" src="https://user-images.githubusercontent.com/91889241/163897104-30583780-9c25-4f67-8542-04af390c17ab.png">

### *Reducing Data Dimensions Using PCA*
<img width="285" alt="Screen Shot 2022-04-18 at 7 28 43 PM" src="https://user-images.githubusercontent.com/91889241/163897298-c824d1f2-4f4c-4ee5-bbe0-b7750bcdc01e.png">

### *Clustering Cryptocurrencies Using K-means*
- Elbow Curve to Find Best Value for K
<img width="715" alt="Screen Shot 2022-04-18 at 7 29 41 PM" src="https://user-images.githubusercontent.com/91889241/163897393-e9685372-e129-4880-87cd-e7df0a2b2b87.png">

- New DataFrame Including Predicted Clusters
<img width="866" alt="Screen Shot 2022-04-18 at 7 31 41 PM" src="https://user-images.githubusercontent.com/91889241/163897491-b2b45c0d-71ad-4a37-aa2b-a4d9e76ae22c.png">


### *Visualizing Cryptocurrencies Results*
- 3D Scatter with PCA Data and Clusters
<img width="815" alt="Screen Shot 2022-04-18 at 7 32 49 PM" src="https://user-images.githubusercontent.com/91889241/163897567-bc2d4b0a-6efd-4f9d-8af1-0f78f297262b.png">

- New DataFrame with Scaled Data of the Clustered_DF index
<img width="459" alt="Screen Shot 2022-04-18 at 7 35 25 PM" src="https://user-images.githubusercontent.com/91889241/163897764-89078c16-8dd1-4ed0-be57-4c1fe72466f9.png">

- Scatter Plot Using Total Coins Mined and Total Coin Supply
<img width="715" alt="Screen Shot 2022-04-18 at 7 36 30 PM" src="https://user-images.githubusercontent.com/91889241/163897840-9fd37378-6986-4220-a4a1-dabb51a4183c.png">
