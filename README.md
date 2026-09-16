# 📚 Books Web Scraping

A Python web scraping project that collects structured book information from **Books to Scrape**, a demo website designed for web scraping practice.

The project extracts book data across multiple categories and pages, then organizes the results into a structured Pandas DataFrame and exports the final dataset as a CSV file.

---

<div align="center">

### 🚀 **Run Directly in Google Colab**

The complete web scraping workflow—from category discovery and dynamic pagination to raw data cleaning and CSV export—is pre-configured and ready to run in the cloud with zero setup required.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-72q64iXKc2h5QqL-ol0kUGI5oBkqOOw)

</div>

---
# See it on google colabe
https://colab.research.google.com/drive/1-72q64iXKc2h5QqL-ol0kUGI5oBkqOOw

## 🎯 Project Overview

The goal of this project is to practice and demonstrate practical web scraping skills, including:

* Sending HTTP requests
* Parsing HTML pages
* Extracting structured information from HTML
* Handling multiple categories
* Handling pagination
* Building a structured dataset with Pandas
* Exporting scraped data to CSV

## 🛠️ Technologies Used

* **Python**
* **Requests** — HTTP requests and website access
* **BeautifulSoup** — HTML parsing and data extraction
* **Pandas** — Data organization and dataset creation
* **Regular Expressions** — Text processing

## 🔎 Data Collected

The scraper collects the following information for each book:

| Column         | Description           |
| -------------- | --------------------- |
| `category`     | Book category         |
| `title`        | Book title            |
| `price`        | Book price            |
| `availability` | Availability status   |
| `rating`       | Book rating           |
| `book_url`     | URL of the book page  |
| `img_src`      | URL of the book image |

## ⚙️ Scraping Process

The project follows these main steps:

1. Connect to the website using `Requests`.
2. Fetch and parse the homepage using `BeautifulSoup`.
3. Extract the available book categories and their URLs.
4. Visit each category.
5. Handle pagination to collect books from multiple pages.
6. Extract the required information for each book.
7. Store the collected records in a Python list.
8. Convert the results into a Pandas DataFrame.
9. Export the final dataset to `all_books_dataset.csv`.

## 📂 Project Structure

```text
books-web-scraping/
│
├── Books_Web_Scraping.ipynb
├── all_books_dataset.csv
├── README.md
└── requirements.txt
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/books-web-scraping.git
cd books-web-scraping
```

### 2. Install the required libraries

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open:

```text
Books_Web_Scraping.ipynb
```

and run the cells in order.

## 📊 Output

The final scraped data is stored in:

```text
all_books_dataset.csv
```

The dataset contains structured book-level information that can be used for further data analysis and exploration.

## 🌐 Source Website

The project uses **Books to Scrape**, a sandbox website created specifically for practicing web scraping.

Website: https://books.toscrape.com/

## ⚠️ Note

Books to Scrape is a demo website for web scraping practice. The website itself notes that its prices and ratings are randomly assigned and do not represent real-world values.

## 📌 What I Practiced

Through this project, I practiced:

* Web scraping with Python
* HTML structure inspection
* CSS selectors and HTML parsing
* URL handling
* Category-based scraping
* Pagination handling
* Data extraction
* Data structuring with Pandas
* CSV export

## 👩‍💻 Author

**Shahd Ayman**
**ashayman111@gmail.com**
Computer Science & Artificial Intelligence Student
Cairo University

Interested in **Data Analysis, Machine Learning, and Web Scraping**.

