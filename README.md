# 🌐 WHO Disease Outbreak News Web Scraping Project

## 📌 Project Overview
This project aims to scrape the Disease Outbreak News (DON) section from the World Health Organization (WHO) website. The goal is to extract key information such as:

- Date of outbreak  
- Disease name  
- Country affected  
- Link to the news article  

The data spans from **1996 to the present**, enabling comprehensive analysis and visualization of global disease outbreaks over time.

---

## 🚀 Why This Project?
Manual collection of outbreak data is time-consuming and error-prone. By automating this process with web scraping, we can:

- Track disease trends globally  
- Identify frequently occurring diseases  
- Visualize geographic and temporal patterns  
- Support public health research and decision-making  

---

## 🧪 Key Features

- ✅ Automated scraping using Selenium and BeautifulSoup  
- ✅ Data saved in a structured format (CSV)  
- ✅ Includes links for further reading on each outbreak  
- ✅ Supports historical data analysis from 1996 onward  
- ✅ Includes WordCloud generation for disease frequency visualization  

---

## 🛠️ Technologies Used

- **Python** : Programming language  
- **Selenium** : For navigating and rendering JavaScript-heavy pages  
- **BeautifulSoup** : For parsing HTML content  
- **Pandas** : For data manipulation and CSV export  
- **WordCloud & Matplotlib** : For visualizing frequent diseases  

---

## 📁 File Structure

```
/who-disease-outbreak-scraper/
│
├── webscraping_project.ipynb   # Main scraping script
├── webscraping_project.html    # HTML version
├output/                          # Folder to store all output files
|   ├── who_webscraping.csv          # Final scraped data in CSV format
|   ├── disease_outbreak_news.json   # Scrape data in JSON format
|   ├── output_who.pkl               # Pickle file for Python object storage
|   └── output_who.txt               # Plain text version of dataset
└── README.md               # Project documentation
```

---

## 📦 Installation Requirements

Install the required Python libraries:

```bash
pip install selenium beautifulsoup4 pandas matplotlib wordcloud webdriver-manager
```

Also required:
- ChromeDriver (compatible with your Chrome browser version)  
- Internet access to load WHO pages  


## 📊 Data Sample Format

```
28 March 2025, Cholera, NA, https://www.who.int/emergencies/disease-outbreak-news/item/
30 September 2024, Marburg virus disease, Rwanda, https://www.who.int/emergencies/disease-outbreak-news/item/
20 September 2024, Avian Influenza A(H9N2), Ghana, https://www.who.int/emergencies/disease-outbreak-news/item/
```

---

## 📈 Further Analysis Ideas

1. **Disease Frequency Visualization**  
   Use `wordcloud.py` to generate a word cloud showing the most commonly reported diseases.

2. **Temporal Trends**  
   Analyze how often certain diseases occur over decades.

3. **Geographic Mapping**  
   Map outbreaks by region to identify hotspots.

4. **Outbreak Correlation**  
   Study co-occurrence of diseases in specific regions or timeframes.

---

## 📝 Notes

- Some older entries may not include country names.  
- The scraper handles pagination automatically.  
- If errors occur during scraping (e.g., timeouts), the script logs the current page and stops gracefully.  

---

## 🧾 License

This project is open source under the **MIT License**.

---

## 👤 Contact

For questions or improvements, feel free to reach out at **leihu.uw@gmail.com** or submit an issue/pull request.

---

Thank you for using this project! Let’s help track global health trends together. 🌍
