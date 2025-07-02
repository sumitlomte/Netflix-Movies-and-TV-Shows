# 🎬 Netflix movie tv_show clustering recommendation
![DALL·E 2025-03-17 19 38 40 - A simple and clean template for a Netflix Movies and TV Shows Clustering machine learning project  The design should feature a minimalistic Netflix-th](https://github.com/user-attachments/assets/7c8c4397-1720-4ef2-81e4-3c2dcf96d09e)

## 📌 Project Overview
This project performs clustering on Netflix movies and TV shows using machine learning techniques. The dataset consists of various features such as title, genre, release year, cast, and ratings, which are used to group similar content together.

## 📂 Dataset
The dataset used for this project is **Netflix Movies and TV Shows**, which contains information on various titles available on Netflix, including:
- Title
- Type (Movie/TV Show)
- Genre
- Release Year
- Cast
- Country of Origin
- Rating
- Duration
- Description

## 🔄 Project Workflow
1. **Data Preprocessing:**
   - Cleaning and handling missing values.
   - Feature engineering.
   - Converting categorical data into numerical representations.
   
2. **📊 Exploratory Data Analysis (EDA):**
   - Understanding the distribution of movies and TV shows.
   - Visualizing trends over the years.
   - Identifying popular genres.
   
3. **🧩 Clustering Approach:**
   - Using techniques such as K-Means, DBSCAN, or Hierarchical Clustering.
   - Applying feature selection and dimensionality reduction (e.g., PCA, TF-IDF for text-based features).
   
4. **📈 Model Evaluation:**
   - Determining the optimal number of clusters.
   - Evaluating cluster quality using silhouette score and other metrics.

## 🛠 Installation
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook netflix-movies-and-tv-shows-ml-project.ipynb
   ```

## 📦 Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK (for text preprocessing)
- Jupyter Notebook

## 📊 Results
![image](https://github.com/user-attachments/assets/40f98e86-4472-4bb3-8f35-bb02b224bc10)
![image](https://github.com/user-attachments/assets/64fb0084-fa87-4d12-a463-fb70af6bc5c5)
![image](https://github.com/user-attachments/assets/5e87f285-9468-466b-9558-155b785fbae1)





## 🚀 Future Improvements
- Incorporate deep learning models for better clustering.
- Improve recommendations based on user preferences.
- Integrate an interactive dashboard for visualization.



