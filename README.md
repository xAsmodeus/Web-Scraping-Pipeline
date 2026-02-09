<h1 align="center">  Web Scraping Pipeline </h1>

---

## 📑 Table of Contents
- [Overview](#overview)
- [Approach](#approach)
  - [Results](#results)
- [Technology Stack](#teck-stack)
- [License](#license)
- [Credits](#credits)

---

## 🧭 Overview

A **web scraping pipeline** that gathers verified business contact data from publicly available directories across selected industries. 

1. Collects and saves all winery profile URLs from [Europages](https://www.europages.co.uk/en/search?isPserpFirst=1&q=winery+supplies)
2. Visits those pages (or linked websites), extracts valid email addresses.
3. Produces and submits the final cleaned datasets(CSV).

The pipeline must follow this exact format.

|NAME|EMAILS|COUNTRY|
| :--------------------- | :--------------------- | :--------------------- |
| | |  |
| | |  |
| | |  |

|NAME|LINK|
| :--------------------- | :--------------------- |
| | | 
| | | 
| | | 

---

## 🛠️ Approach

**Step 1 – Setup**
- Imported the libraries.
- Identified the 3 source pages.

**Step 2 – Data Extraction**
- Scraped data from each page.
- Saved each page’s `.html` links into separate CSV files.

**Step 3 – Data Merging**
- Merged the three CSV files into one master file.

**Step 4 – URL Construction**
- Combined the standard base URL with the variable link parts.
- Generated full industry URLs.

**Step 5 – Final Outputs**
- Created `NAME | LINKS` CSV.
- Created `NAME | EMAILS | COUNTRY` CSV.

---

## 📊 Results

1) `NAME | LINK(.html)`

<img width="500" height="400" alt="Screenshot_2" src="https://github.com/user-attachments/assets/bdc0d49c-c00b-4174-b60f-04ee3528b78c" />

2) `NAME | LINK`

<img width="500" height="400" alt="Screenshot_2" src="https://github.com/user-attachments/assets/602d7b3f-cd6f-4a35-8276-b882e1680a10" />

3) `NAME | LINK | COUNTRY`

<img width="500" height="400" alt="Screenshot_1" src="https://github.com/user-attachments/assets/d2219e97-a242-4160-bd5c-20b72cdad170" />

---

## 🧰 Technology Stack

- **Language:** Python (v to be updated)
- **Modules:**
  - `requests` 
  - `BeautifulSoup (bs4)` 
  - `pandas` 
  - `urllib.parse` 
  - `re` 
- **Platform:** Google Colab

---

## 🛡️ Licence

MIT [License](LICENSE/) 

---

## 🙌 Credits 🚧under construction🚧

