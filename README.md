# 📖 Scrape_quotes_universe - Web Scraping & Data Analysis Project

## 📝 Overview
Scrape_quotes_universe is a project that involves scraping quotes data from the website Quotes to Scrape using BeautifulSoup, storing it in a structured format, and performing data analysis with SQL and Python. The project includes data collection, data storage, SQL querying, and data visualization to extract meaningful insights from the scraped quote data.

## **Team Members**
- **Anas Zaki**
- **Vishal Singh**

## 📂 Project Structure
```
Scrape_quotes_universe/
│── 📄 README.md                 # Project documentation
│── 📂 data/                   # Contains raw and processed datasets
│   │── 📄 Quotes__.csv          # Scraped quote data
│── 📂 notebooks/              # Jupyter notebooks for analysis
│   │── 📄 web_scraping.ipynb    # Web scraping script using BeautifulSoup
│   │── 📄 EDA.ipynb             # Exploratory Data Analysis notebook
│   │── 📄 sql.ipynb             # SQL queries for extracting insights
```

## 🌐 Web Scraping
In this project, quotes are scraped from the **[Quotes to Scrape]**(https://quotes.toscrape.com/) website using **Python** and **BeautifulSoup**. The key data points scraped include:

- **Quote text** 💬 : The actual quote text.
- **Author** ✍️ : The author of the quote.
- **Tags** 🔖 : Associated tags for each quote (e.g., Inspirational, Life, etc.).


This data is scraped from multiple pages and saved in a CSV file for further analysis.

## 🗄️ Data Storage & Processing
After scraping the data, it is cleaned and structured properly. Missing values are handled, formats are corrected, and the data is stored in the **Quotes__.csv file**.

## 🛠️ SQL Queries
The project uses **MySQL** for storing the scraped data and running various SQL queries to extract insights, such as:

- Counting the number of quotes by each author.
- Identifying the top 5 most common tags.
- Finding the longest quote and its author.
- Analyzing quotes that contain specific words.

SQL queries are executed with the help of **Python** and **MySQL Connector** to interact with the database.


## 📊 Exploratory Data Analysis (EDA)
The project performs Exploratory Data Analysis (EDA) using **Pandas**, **Matplotlib**, and **Seaborn**. Key visualizations include:

- Distribution of quote lengths.
![image](https://github.com/user-attachments/assets/9e3061f6-f740-4a3a-ace7-0b8fc3bea793)

- Most common words in quotes.
![image](https://github.com/user-attachments/assets/e7b3eedc-3546-4025-973a-93a5ccf0401c)

- Bar charts for the most quoted authors.
![image](https://github.com/user-attachments/assets/dab4945e-3b4e-4f31-9e66-a6ec8a7d7426)

- Tag distribution in pie charts.

![image](https://github.com/user-attachments/assets/dea4c5cb-d430-463e-a4aa-5e98bc1e32ed)


## 📌 Key Features
✔️ **Web scraping** for automated data collection.  
✔️ **Data storage** and analysis with **MySQL**.  
✔️ **Exploratory Data Analysis (EDA)** with visualizations.  
✔️ Clean and well-documented code structure.

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/rajput5540/Scrape_quotes_universe.git
   cd Scrape_quotes_universe
   ```
2. **Install required libraries:**
- `requests`
- `beautifulsoup4`
- `pandas`
- `matplotlib`
- `seaborn`
- `mysql-connector-python`
  
You can install them using pip:
   ```bash
  pip install requests beautifulsoup4 pandas matplotlib seaborn mysql-connector-python
   ```
3. **Run the web scraping script**: The scraping script is located in the `notebooks/web_scraping.ipynb`. This will collect data and save it to the `Quotes__.csv file`.
   
5. **Connect to MySQL and insert data**: Use the Python `mysql-connector` library to connect to your MySQL database and insert the data into the quotes table.
   
7. **Perform EDA and Visualization in Jupyter Notebook**: The EDA and SQL queries are located in the `notebooks/EDA.ipynb` and `notebooks/sql_queries.ipynb` files.

## 🚀 Future Improvements
- Implement **real-time quote scraping**.
- Enhance **visualizations** with interactive plots.
- Integrate **machine learning** for sentiment analysis of quotes.

## 📜 License
This project is open-source and available for modification and distribution.

---

📩 **Contributions & Feedback**
Feel free to fork the repository, submit issues, or suggest improvements!


Happy Coding! 🚀
