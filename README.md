📊 Restaurant Review & Engagement Analysis
This repository contains an exploratory data analysis (EDA) of restaurant reviews, tips, check-ins, and user engagement, with a focus on comparing Elite vs Non-Elite user activity using the Yelp dataset.

🧾 Notebook: restaurant-analysis.ipynb  ( https://www.kaggle.com/code/kaifkhan123/restaurant-analysis )
📂 Datasets: ( https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset )
The notebook covers:

📈 Time-series analysis of average ratings and engagement.
👑 Elite vs Non-Elite user review behavior.
⏰ Hourly distribution of tips, reviews, and check-ins.
📊 Visual comparisons using pie charts, bar charts, and seasonal decomposition.

📂 Project Structure
├── restaurant-analysis.ipynb
├── images/
│   ├── avg_rating_over_time.png
│   ├── elite_user_distribution.png
│   ├── review_distribution_by_hour.png
│   └── seasonal_decomposition_tips.png
├── README.md

📷 Key Visualizations
🧑‍🍳 1. Elite vs Non-Elite User Distribution
🕓 2. Hourly Review and Tip Counts
🌡️ 3. Average Rating Over Time
📉 4. Tip Count Seasonal Decomposition

⚙️ Technologies Used
Python 3.x
Pandas, NumPy – Data manipulation
Matplotlib, Seaborn – Visualization
SQLite – Data source
Statsmodels – Seasonal decomposition

🚀 How to Run
Clone the repository:

git clone https://github.com/yourusername/restaurant-analysis.git
cd restaurant-analysis
Install dependencies:

pip install -r requirements.txt
Launch the notebook:



🧠 Insights
Elite users are fewer but contribute a higher volume of reviews.
Engagement patterns vary by hour, with peak times around meal hours.
Average ratings have seasonal variations.

📝 License
This project is licensed under the MIT License.

✅ To Do
 Add sentiment analysis on reviews.
 Predict future check-in trends.
 Deploy as a Streamlit dashboard.
