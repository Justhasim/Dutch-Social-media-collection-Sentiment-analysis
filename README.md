# Dutch-Social-media-collection-Sentiment-analysis
Sentiment analysis on a large Dutch tweet dataset using TextBlob, with geolocation filtering, visualizations (pie charts, word clouds, heatmaps), and top user sentiment insights.

---

## 📂 Dataset

Due to file size limitations, the dataset is not included in this repository.

📥 You can download the full dataset from Kaggle:  
🔗 [Dutch Tweets Dataset – Skylord](https://www.kaggle.com/datasets/skylord/dutch-tweets?resource=download)

After downloading, place all 10 `.json` files in a folder named `data/`.

---

## 🚀 Features

- 📥 Loading and merging multi-part JSON dataset
- 🧹 Text cleaning and preprocessing
- 📌 Coordinate filtering to focus only on the Netherlands
- 💬 Sentiment scoring using **TextBlob**
- 📊 Pie chart showing sentiment distribution
- ☁️ Word clouds for each sentiment class
- 🌍 Heatmap of tweet activity (using **Folium**)
- 🧑‍💻 Identification of users with the most positive/negative/neutral tweets
- 🧠 Detection of duplicate tweets

---

## 📊 Sentiment Analysis Logic

Using `TextBlob`:
- Polarity > 0 → **Positive**
- Polarity < 0 → **Negative**
- Polarity = 0 → **Neutral**

Each tweet is classified accordingly and stored in a new `sentiments_label` column.

---

## 📸 Visual Outputs

- ✅ Pie chart of sentiment distribution
- ✅ Word clouds of top words per sentiment
- ✅ Folium heatmap of tweet locations

---

## 🛠 How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/skylord/dutch-tweets?resource=download)
2. Place all JSON files inside a folder named `data/`

