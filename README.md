# 📊 Netflix Data Analysis Project

This project explores patterns and trends in Netflix content using a dataset of movies and TV shows. By analyzing attributes such as **genre**, **type**, **rating**,
**release year**, **runtime**, and **country**, we gain valuable insights into how Netflix's content is structured and consumed.

## 🔍 Objectives

- Understand the distribution of content types (Movies vs. TV Shows)
- Analyze the most popular genres on Netflix
- Explore trends in content ratings and release years
- Compare runtime of movies vs. TV shows
- Visualize relationships between genre, type, rating, and country
- Identify trends in content maturity and audience targeting

## 📁 Dataset

- Source: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Format: CSV
- Columns: `title`, `type`, `genre`, `country`, `rating`, `release_year`, `duration`, etc.

## 📌 Key Findings

- **Movies dominate Netflix's content** but TV Shows have longer runtimes.
- **Drama, Comedy, and Action** are the most common genres globally.
- Most content falls under **TV-MA** and **TV-14**, showing a tilt towards mature audiences.
- Genres like **Action** and **Reality** are more likely to be rated mature.
- Countries like the **United States**, **India**, and the **UK** produce the majority of Netflix content.

## 📊 Visualizations Included

- Content Type Distribution
- Genre Frequency Chart
- Rating vs. Type
- Runtime Distribution (Movies vs. TV Shows)
- Country vs. Type
- Genre vs. Rating Heatmap
- Top Genre by Country and Rating (Multi-feature plots)

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 📄 Output

You can find the final visualizations and notebook in this repository.

## ✅ How to Run

# Clone the repository
git clone https://github.com/umeehani802/netflix_trends-analysis.git

# Navigate into the project directory
cd netflix_trends-analysis

# Install required dependencies
pip install pandas matplotlib seaborn jupyter

# Launch Jupyter Notebook
jupyter notebook
