#### Recommendation of products to online grocer customers based on similarity of their orders

csv_files : Directory containing data files

Final Report Capstone 2.docx : Final report

Instacart_Final.ipynb : Final Ipython notebook

Presentation Capstone 2.pptx : Presentation slides

Project Proposal for Capstone 2.docx : Project description

#### The focus of this project was on providing personalized product recommendations to online grocer customers (Instacart's customers):

i) Instacart's publicly available data was obtained from Kaggle (about 3.4M orders, about 200K users, about 50K products)

ii) Features that represented the behavioral attributes of the users were selected to cluster the orders using k-means algorithm

iii) Since each user had multiple orders, each user ended up having multiple cluster labels. The dominant/most frequent cluster label was chosen for a user and was assigned as the "cluster label" for the user

iv) Top 15 products for each cluster were identified

v) For each user, products that had not been purchased out of the top 15 products corresponding to the user's "cluster label" were identified and were recommended to the user





