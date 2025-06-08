# 📘 Book Price Analysis Project

This project is a complete data-driven pipeline to **scrape**, **analyze**, and **visualize** book pricing data. It is ideal for publishers, resellers, or data analysts who want to understand book pricing trends, spot outliers, and derive actionable insights from online bookstores.

---

## 🔎 Features

- 🕸️ **Web Scraping**: Automatically collects book data (title, price, rating, etc.) from an online bookstore.
- 🧼 **Data Cleaning**: Handles missing values, inconsistent formats, and ensures data is analysis-ready.
- 📊 **Statistical Analysis**: Calculates mean, median, mode, standard deviation, and identifies price outliers.
- 📈 **Data Visualization**: Plots price distributions, rating vs price trends, and other insightful charts using Matplotlib/Seaborn.
- 📂 **Structured Notebook**: Easy-to-read and modify Jupyter notebook with well-documented cells.

---

## 🛠️ Technologies Used

- **Python 3.x**
- `requests`, `BeautifulSoup` – for web scraping
- `pandas`, `numpy` – for data processing
- `matplotlib`, `seaborn` – for visualization
- `jupyter` – for development and documentation

---

## 🗂️ Project Structure

book-price-analysis/
│
├── book_price_analysis.ipynb # Full Jupyter notebook with scraping, cleaning & analysis
├── books.csv # Exported dataset of scraped books
├── README_book_price_analysis.md # Project-specific README file
├── assets/ # Charts and screenshots
└── requirements.txt # (Optional) List of required packages

### 1. Clone the repository

```bash
git clone https://github.com/ndjichou-elie/ndjichou-elie.github.io.git
cd book-price-analysis

## 🚀 How to Use
1-Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
2- Install dependencies
pip install -r requirements.txt
3- Launch the notebook
jupyter notebook

Then open book_price_analysis.ipynb.



📬 Contact
Email: elie.ndjichou@facsciences-uy1.cm

LinkedIn: Ndjichou Elie

Portfolio: Visit Portfolio
