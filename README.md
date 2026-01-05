📚 E-Commerce Web Scraper (Tkinter GUI)
📌 Project Description

This project is a GUI-based E-Commerce Web Scraper developed using Python and Tkinter.
It allows users to scrape product data from:

books.toscrape.com (demo e-commerce site)

Any custom e-commerce website (basic generic scraping)

The application extracts product details such as title, price, rating, category, description, image URL, and displays them in an interactive graphical interface. Scraped data can be exported in CSV, JSON, or TXT format.

🎯 Objectives

To understand web scraping using BeautifulSoup

To implement multithreading for smooth GUI performance

To design a user-friendly desktop application

To store and export scraped data in structured formats

🛠 Technologies Used

Python 3

Tkinter – GUI design

BeautifulSoup (bs4) – HTML parsing

Requests – HTTP requests

Threading & Queue – Background scraping

JSON / CSV – Data export

📂 Project Features

✔ GUI-based interface (no command line needed)
✔ Scrape predefined website (books.toscrape.com)
✔ Scrape custom e-commerce websites
✔ Set maximum pages and product limits
✔ Live log messages during scraping
✔ Preview scraped data
✔ Statistics (price, rating, category analysis)
✔ Export data to CSV / JSON / TXT
✔ Stop scraping anytime

🖥 Application Screens

The GUI contains:

Controls Panel (left side)

Log Tab – live scraping logs

Data Tab – table view of products

Preview Tab – JSON preview

Statistics Tab – insights from data

⚙️ How It Works (Logic)

User selects website type (Books or Custom URL)

User sets:

Maximum pages

Maximum products

Scraping starts in a separate thread

HTML pages are fetched using requests

Data is extracted using BeautifulSoup

Results are displayed in the GUI

User can export the data# web-scraper
