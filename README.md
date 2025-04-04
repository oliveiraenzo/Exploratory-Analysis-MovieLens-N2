# 🎬 N2 Assignment – Exploratory Data Analysis with MovieLens

This repository contains the solution to the **N2 assessment** for the **1st Term** in the Data Analysis course.  
The objective is to perform an **exploratory data analysis** using the [MovieLens (Small)](https://grouplens.org/datasets/movielens/) dataset and answer key questions about user behavior and movie characteristics.

---

## 📌 About the Project

- 🗓️ **Academic Assignment** – 1st N2  
- 🧠 **Topic**: Exploratory Data Analysis (EDA)  
- 📚 **Dataset**: MovieLens (Small), with information on movies, ratings, tags, and links.  
- 👥 **Group Work**: Each member contributed individual questions based on different data files.  

---

## 📁 Project Structure

```bash
atividade-n2-movielens/
├── data/                     # Dataset files (.csv)
├── notebook/
│   └── atividade_n2_movielens.ipynb  # Main analysis notebook
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## ✅ Evaluation Criteria & Questions

### 📊 Question 1 – Exploratory Analysis

#### (a) Is there any correlation between movie release year and average rating?
> A weak negative correlation of ≈ `-0.350` was found. Older movies tend to have slightly higher average ratings, possibly due to classic status or survival bias.

#### (b) Which group shows more variation: users who rated or users who tagged?
> Rating users showed greater variation (higher standard deviation and wider distribution). Tagging behavior was more consistent across users.

#### (c) What is the most frequent tagged category?
> The tag **"IN NETFLIX QUEUE"** appeared **131 times**, making it the most frequently used label.

#### (d) How are ratings distributed over time?
> The temporal analysis revealed periods of peaks and variation, reflecting trends in user engagement and popular movie releases.

---

### 🙋‍♂️ Question 2 – Individual Questions (Each student selected one dataset)

#### **From `movies.csv`**
- **How many unique genres are there?** → `20`  
- **Most frequent genre?** → `Drama` with `4,361` movies  

#### **From `tags.csv`**
- **How are tag creation dates distributed?**  
  Shows growth and peak periods in user interaction.
- **Which movies received the most tags?**  
  - Movie ID 296 → `173` tags  
  - Movie ID 2959 → `48` tags  

#### **From `ratings.csv`**
- **Is there a correlation between number of ratings and average rating?**  
  Moderate correlation, suggesting popular films often receive higher scores.
- **How does user activity evolve over time?**  
  Analysis reveals seasonal or year-based rating spikes.

#### **From `links.csv`**
- **Any duplicate `movieId` entries?** → `No`  
- **Basic structure:**  
  - `9742` rows  
  - `3` columns: `movieId`, `imdbId`, `tmdbId`

---

### 🔗 Question 3 – GitHub Repository

This repository contains all content in a single **Jupyter Notebook** as requested.

📎 **Repository URL**: [https://github.com/your-username/atividade-n2-movielens](https://github.com/your-username/atividade-n2-movielens)

---

## ⚙️ How to Run

Make sure you have Python installed (version 3.8+ recommended). Then:

```bash
# Clone the repository
git clone https://github.com/your-username/atividade-n2-movielens.git
cd atividade-n2-movielens

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebook/atividade_n2_movielens.ipynb
```

---

## 📦 Dependencies

Main libraries used:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn` (for correlation analysis)

See `requirements.txt` for full details.

---

## 👥 Authors

This project was developed by:

- **Student 1** – Enzo Brito Aves de Oliveira
- **Student 2** – Heitor Santos Ferreira
- **Student 3** – Jackson Gomes Cerqueira
- **Student 4** – Tainara do Nascimento Casimiro
