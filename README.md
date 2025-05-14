# 🕸️ Web Scraping with Python: AI News, Amazon Prices & Weather Insights

This project demonstrates how to collect real-world data from the web using Python. It covers scraping **AI-related news articles**, **product prices from Amazon**, and **weather reports** from two reliable sources. A bonus task showcases how to automate CAPTCHA clicking using **Selenium**.

Developed to showcase a variety of web scraping techniques, it uses `requests`, `BeautifulSoup`, and `Selenium`, and stores the data in `.csv` and `.txt` formats for further analysis or automation workflows.

---

## 📌 Project Objectives

- Extract unstructured and structured content from websites
- Automate scraping using Selenium for dynamic pages
- Handle real-world anti-bot mechanisms (CAPTCHA)
- Save and format data for reuse in analytics pipelines

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `TASK 01_DQ_Lab1.ipynb` | Scrapes two AI-related articles and stores content in text format |
| `TASK 02_DQ_Lab1.ipynb` | Scrapes Amazon product title and price for Apple Watch Band |
| `TASK 03_DQ_Lab1.ipynb` | Scrapes weather data from TimeAndDate.com and Wunderground.com |
| `Lab1-Bonus Task.ipynb` | Demonstrates CAPTCHA solving using Selenium |
| `AmazonDataset.csv` | Output from Task 2 – product name and price |
| `Task1_1.txt` / `Task1_2.txt` | News article content scraped from AI-related sources |
| `timeanddate_weather.txt` / `wunderground_weather.txt` | Scraped weather data |
| `captcha_solved.png` (optional) | Screenshot showing CAPTCHA automation success |
| `README.md` | Project overview and instructions |

---

## 🔍 Sites Scraped

1. **AI News Articles**
   - [ComputerWeekly: AI in Olympics](https://www.computerweekly.com/news/366588823/Artificial-intelligence-to-make-Olympic-Games-more-inclusive)
   - [MIT Sloan: Machine Learning Explained](https://mitsloan.mit.edu/ideas-made-to-matter/machine-learning-explained)

2. **E-Commerce**
   - [Amazon.se – Apple Watch Band product details](https://www.amazon.se/)

3. **Weather**
   - [TimeAndDate](https://www.timeanddate.com/weather/)
   - [Wunderground](https://www.wunderground.com/)

4. **Bonus: CAPTCHA**
   - [NopeCHA Demo Page](https://nopecha.com/demo)

---

## 🛠️ Tools & Libraries Used

- `requests` – HTTP requests
- `BeautifulSoup4` – HTML parsing
- `csv`, `os` – File handling
- `Selenium` – Browser automation
- `webdriver-manager` – Chrome driver management
- `time`, `datetime` – Waits and formatting
- `IPython.display` – Display control (for Jupyter)

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/kushitec15691/web-scraping-project-python
cd web-scraping-project-python
