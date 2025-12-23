# FlipKart_Web_scarpping_project
# 📱 Flipkart Mobile Phones Web Scraping & Analysis

## 📌 Project Overview
This project demonstrates **web scraping, data cleaning, and exploratory data analysis (EDA)** using Python.  
Mobile phone data is scraped from **Flipkart**, cleaned, structured, and analyzed to understand pricing trends, ratings, and key specifications.

The project simulates a **real-world data analyst workflow** — from raw web data to insights and visualizations.

---

## 🛠️ Tools & Technologies
- **Python**
- **Requests** – to send HTTP requests  
- **BeautifulSoup** – to parse HTML and extract data  
- **Pandas** – for data cleaning and manipulation  
- **Matplotlib** – for data visualization  

---

## 📂 Dataset Details
The following attributes are extracted and processed:

- Mobile Name  
- Price (₹)  
- Rating  
- Specifications  
- Brand  
- RAM (GB)  
- Storage (GB)  
- Battery Capacity (mAh)  

### Generated Files
- `flipkart_raw_mobiles.csv` – raw scraped data  
- `flipkart_cleaned_mobiles.csv` – cleaned dataset  
- `final_flipkart_dataset.csv` – final structured dataset  

---

## 🔄 Project Workflow
1. Send request to Flipkart search page  
2. Parse HTML using BeautifulSoup  
3. Extract mobile phone details  
4. Store raw data into CSV  
5. Clean price, ratings, and specifications  
6. Extract RAM, storage, battery, and brand  
7. Perform exploratory data analysis  
8. Generate visual insights  

---

## 📊 Exploratory Data Analysis (EDA)
The following visualizations are created:

- **Price Distribution of Mobile Phones**
- **Price vs Rating Relationship**
- **Battery Capacity Distribution**

Saved charts:
- `price_distribution.png`
- `price_vs_rating.png`
- `battery_distribution.png`

---

## 📈 Key Insights
- Mobile prices vary widely across brands and specifications  
- Higher-priced phones tend to have slightly better ratings  
- Most phones fall within a common battery capacity range  

These insights help understand **market positioning and consumer preferences**.

---

## ⚠️ Disclaimer
This project is created **for educational purposes only**.  
Flipkart’s website structure may change, which can affect scraping results.  
Always respect a website’s **terms of service** before scraping.

---

## 👩‍💻 Author
**Anisha Waikar**  
Aspiring Data Analyst | SQL | Excel | Python | Power BI  

📌 Project available on my **GitHub profile**

---

## ⭐ How to Run the Project
```bash
pip install requests beautifulsoup4 pandas matplotlib
python flipkart_scraping_project.py
