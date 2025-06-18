# 🎬 MongoLens: Insights into Movie Trends with MongoDB & Python

This project explores the MovieLens dataset using MongoDB for non-relational data handling and Python for querying, analysis, and visualization. It aims to uncover patterns in movie popularity, user preferences, genre evolution, and rating behaviors over time.

## 📦 Project Structure
  ```bash
├── notebooks/
│ └── dataWrangling.ipynb # Data loading, merging, transformation & JSON export
│ └── extra.ipynb # MongoDB queries & visualizations using Python
├── merged_movies_ratings.json # Final processed dataset
├── dump/ # intermediate datasets
├── Pictures/
├── SMBUD Project - Federica Topazio.pdf # Full report
├── README.txt # Citations of dataset
└── README.md # This file
  ```


## 🗃 Dataset

MovieLens 100k dataset containing:
- ~100,000 ratings from 610 users
- 9,742 movies with genre metadata
- Timestamps for all ratings (from 1996 to 2018)

**Main fields:**
- `userId`, `movieId`, `title`, `genres`, `rating`, `timestamp`, `release year`

## 🔧 Technologies Used

- **MongoDB**: flexible document-based schema & aggregation queries
- **Python** (pandas, matplotlib, seaborn, pymongo): data wrangling and visualization
- **Jupyter Notebooks**: analysis and execution of Python code

## 🔍 Analysis Topics

### ✅ Data Wrangling (See: `dataWrangling.ipynb`)
- CSV loading, cleaning & transformation
- Genre parsing and timestamp formatting
- Normalization of ratings
- JSON export for MongoDB

### 📊 MongoDB Queries & Visualizations (See: `extra.ipynb`)
- Average rating per genre
- User behavior based on rating activity
- Most polarizing movies (variance in ratings)
- Rating trends over time (e.g., for *Toy Story*)
- Genre popularity and evolution over the years
- Temporal patterns (monthly ratings)
- Correlation between number of ratings and average rating

## 📈 Example Visualizations

- 🎭 Bar chart: average rating per genre  
- 👤 Scatter plot: user engagement vs average rating  
- 🧨 Variance bar chart: most polarizing movies  
- 📆 Line plot: rating trends for specific movies over time  
- 🧊 Heatmap: genre popularity changes by year  
- 📉 Monthly rating trends

## 🧠 Key Learnings

- MongoDB is well-suited for semi-structured datasets with nested lists (e.g., genres)
- Aggregation pipelines enable complex, efficient querying
- Visual exploration of rating patterns can inform recommender systems

## ✍️ Author

**Federica Topazio**  
Politecnico di Milano | Systems and Methods for Big and Unstructured Data (2023–2024)

## 📜 License

This project is licensed for academic and research purposes.
