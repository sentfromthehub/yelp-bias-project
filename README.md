# Detecting Systemic Bias in Hospitality Reviews with the Yelp Open Dataset

This project analyzes Yelp reviews of different hospitality venues such as restaurants, hotels, spas, and nightlife venues in **Edmonton, Nashville, and New Orleans** to detect potential **bias and unfair treatment**. Project was done in the last 2 weeks of August 2025.  

## 📌 Overview
- **Data**: Yelp business + review datasets  
- **Focus**: Hospitality businesses (restaurants, bars, hotels, spas, cafes)  
- **Methods**:  
  - NLP preprocessing + keyword detection  
  - Sentiment analysis w/ VADER  
  - Bias context = negative sentiment + bias keyword
  - Geographic clustering (KMeans) + neighborhood analysis  
  - Visualization w/ Seaborn, Matplotlib & Folium maps  

## ⚙️ Tech Stack
- Python (pandas, numpy)  
- NLTK + VADER sentiment  
- Scikit-learn (KMeans, clustering)  
- Matplotlib / Seaborn (EDA)  
- Folium (heatmaps, geospatial viz)  

## 🚀 How to Run
1. Clone repo and install dependencies  
2. Download the dataset from [here](https://business.yelp.com/data/resources/open-dataset/) and place the Yelp `business.json` and `review.json` files in the project folder.
3. Run Jupyter notebook
