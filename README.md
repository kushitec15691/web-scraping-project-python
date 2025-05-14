# 🕸️ Intelligent Web Scraping with Python – AI News, E-Commerce, and Weather

This project showcases advanced web scraping using Python to extract and organize real-world data from multiple websites. It includes examples of scraping news articles, product pricing, and weather information. It also demonstrates how to handle CAPTCHA with Selenium for automation.

---

## 🎯 Project Goals

- Extract structured and unstructured data from websites
- Store content in CSV and TXT formats
- Automate scraping using Selenium for dynamic pages
- Handle basic CAPTCHA challenges

---

## 📁 Project Contents

| File | Description |
|------|-------------|
| `ai_article_scraper.py` | Scrapes two AI-related news articles and saves content |
| `amazon_price_scraper.py` | Scrapes Amazon product titles and prices |
| `weather_scraper.py` | Scrapes weather data from two different weather sources |
| `AmazonDataset.csv` | Extracted product data (name & price) |
| `timeanddate_weather.txt`, `wunderground_weather.txt` | Extracted weather reports |
| `captcha_solved.png`, `debug_screenshot.png` | CAPTCHA automation screenshots |
| `README.md` | Project overview and documentation |

---

## 🧪 Techniques Used

- `requests` & `BeautifulSoup` for HTML parsing
- `Selenium` + WebDriverManager for browser automation
- File I/O: CSV writing, text extraction
- User-agent spoofing, time delays
- Error handling & screenshot logging

---

## 🔍 Sites Scraped

1. **News**: AI-related articles from real tech news platforms  
2. **E-commerce**: Amazon product details  
3. **Weather**: TimeAndDate.com and Wunderground.com  
4. **CAPTCHA**: [NopeCHA demo](https://nopecha.com/demo) automated click

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/kushitec15691/web-scraping-project-python
