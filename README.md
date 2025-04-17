# 🕸️ Web Scraping Project: Noon Yoga Products

This project is a Python-based web scraper that collects product data related to **Yoga** from the Noon.com e-commerce website and stores it in a CSV file for analysis or further use.

## 📌 Project Objective

To scrape product listings related to Yoga from Noon.com and extract relevant information such as:
- Product Name
- Price
- Category
- Image URL
- Rating (if available)
- Product URL

The scraped data is saved to a file named:  
`noon_yoga_products_all_pages.csv`

---

## 🧰 Tools and Technologies Used

- **Python**
- **Jupyter Notebook** (`.ipynb`)
- **Libraries**:
  - `requests`
  - `BeautifulSoup` (from `bs4`)
  - `pandas`
  - `time` (for request throttling)
  - `csv`

---

## 📂 Files

| File Name                        | Description |
|----------------------------------|-------------|
| `webScraping.ipynb`              | Main Jupyter Notebook containing the scraping logic |
| `noon_yoga_products_all_pages.csv` | Output CSV file containing all scraped product data |

---

## 📦 Features

- Scrapes multiple pages of product data by automatically navigating through paginated URLs.
- Extracts key product information cleanly and handles missing fields gracefully.
- Saves the data in a structured format using `pandas`.
- Includes basic error handling and polite scraping practices (e.g., request delays).

---

## 🚀 How to Run

1. **Clone this repository** (or download the files).
2. Open `webScraping.ipynb` in Jupyter Notebook.
3. Run each cell step-by-step.
4. The final output CSV file will be generated as `noon_yoga_products_all_pages.csv`.

---

## 📝 Sample Output

The CSV file contains the following columns:

- `Product Name`
- `Price`
- `Category`
- `Rating`
- `Image URL`
- `Product URL`

You can open the CSV file using Excel, Google Sheets, or load it into any data analysis tool.


