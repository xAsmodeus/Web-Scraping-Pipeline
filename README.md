<h1 align="center">  Web Scraping Pipeline </h1>

---

## 🔍 Overview

A **web scraping pipeline** that gathers verified business contact data (especially emails) from publicly available directories across selected industries. 

1. Collects and saves all winery profile URLs from Europages.
2. Visits those pages (or linked websites), extracts valid email addresses.
3. Produces and submist the final cleaned datasets(CSV).

The pipeline must follow this exact format.

<img width="500" height="400" alt="Screenshot_1" src="https://github.com/user-attachments/assets/90e7d628-20aa-4955-9bf0-879b68be78dd" />

---

## 🧠 Approach

▶ **Step 1 – Setup**
- Imported the libraries.
- Identified the 3 source pages.

▶ **Step 2 – Data Extraction**
- Scraped data from each page.
- Saved each page’s `.html` links into separate CSV files.

▶ **Step 3 – Data Merging**
- Merged the three CSV files into one master file.

▶ **Step 4 – URL Construction**
- Combined the standard base URL with the variable link parts.
- Generated full industry URLs.

▶ **Step 5 – Final Outputs**
- Created `NAME | LINKS` CSV.
- Created `NAME | EMAILS | COUNTRY` CSV.

<img width="500" height="400" alt="Screenshot_2" src="https://github.com/user-attachments/assets/bdc0d49c-c00b-4174-b60f-04ee3528b78c" />


<img width="500" height="400" alt="Screenshot_2" src="https://github.com/user-attachments/assets/602d7b3f-cd6f-4a35-8276-b882e1680a10" />


<img width="500" height="400" alt="Screenshot_1" src="https://github.com/user-attachments/assets/d2219e97-a242-4160-bd5c-20b72cdad170" />


---

## 🧪 Tests

- Run and tested on Google Colab

---

## 🔗 References
1. https://www.notion.so/digiole/Scalable-Web-Scraping-Pipeline-21425969342680b7a99ef9f999a96f06
2. https://www.europages.co.uk/en/search?isPserpFirst=1&q=winery+supplies
3. https://beautiful-soup-4.readthedocs.io/en/latest/#quick-start
4. https://pandas.pydata.org/docs/user_guide/index.html
5. W3schools
5. Stackoverflow
6. Youtube
7. Chat GPT
8. Gemini AI
9. Geeks for Geeks

---

## ⚖️ Licence
  
