# Data Engineering Project Proposal
## Bag Hunter 

- web scrapping [Farfetch.com](https://www.farfetch.com) fashion products 
- create an end-user app with _Deep Learning_ and _Data Engineering_ recursively updating database


#### Question/Need 

Can my model identify the bag’s brand based on the product image?

To use cloud computing and big data pipelines to create an e-commerce/fashion products images classification(to identify its brand) based on the product images given.

#### Data Description

The data of product information will be web scraping from [Farfetch.com](https://www.farfetch.com) by using API to collect product descriptions and images, etc. Next, I'll create a database to store the data on MongoDB.

I plan to start with one specific category (**as Bag Section**) to build up my model. I’ll take the images of 5 major bags brands – __YSL, Gucci, Prada, Hermes, LV__ for modeling. I'll apply keras deep learning to train the model, then make it to a predict function to take a new image input to identify the bag’s brand. If necessary, I'll use Google Cloud Platform and Google Colab for a more efficient way to deal with big data.

It will be an end-to-end project, I aim to set up the pipeline for the whole process and deploy it into a web application for end-users.


#### Tools
- data collection: API json
- database management: MongoDB
- cloud computing: Google Cloud Platform & Google Colab
- image classification: Deep Learning keras
- app deployment: streamlit



#### MVP
- pipeline setup to get the baseline model running
