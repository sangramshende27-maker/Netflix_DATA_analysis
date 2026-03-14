# 🎬 Netflix Movies & TV Shows Data Analysis

A data analysis project exploring trends, genres, ratings, and popularity metrics from a Netflix titles dataset containing nearly **10,000 entries**.

---

## 📁 Dataset Overview

**File:** `NetflixData.csv`  
**Records:** ~9,827 rows  
**Columns:**

| Column | Description |
|---|---|
| `Release_Date` | Date the title was released |
| `Title` | Name of the movie/show |
| `Overview` | Short plot description |
| `Popularity` | Popularity score (numeric) |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average rating (out of 10) |
| `Original_Language` | Language code (e.g., `en`, `hi`, `ja`) |
| `Genre` | Comma-separated list of genres |
| `Poster_Url` | URL to the title's poster image |

---

## 📊 Project Goals

- Explore popularity and rating distributions across titles
- Identify top-rated and most popular movies/shows
- Analyze genre trends and language diversity
- Visualize release trends over time
- Clean and preprocess data for further ML or BI use

---

## 🗂️ Project Structure

```
netflix-data-analysis/
│
├── NetflixData.csv          # Raw dataset
├── netflix_analysis.ipynb   # Main Jupyter Notebook
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook

```bash
jupyter notebook netflix_analysis.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** – data loading and manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Plotly** – interactive charts
- **Jupyter Notebook** – interactive analysis environment

---

## 📌 Key Insights (Examples)

- Most titles in the dataset are in **English**, followed by Japanese and Hindi.
- **Action, Thriller, and Drama** are the most common genres.
- Titles with higher `Vote_Count` tend to have more stable `Vote_Average` scores.
- Popularity scores vary significantly — a few blockbusters dominate the high end.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
