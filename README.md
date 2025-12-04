                                         ** Runned and Tested in Google Colab **                                           
## 🎯 Context

A **web scraping pipeline** that gathers verified business contact data (especially emails) from publicly available directories across selected industries. 

## 🚀 What it does

1. Collects and saves all winery profile URLs from Europages.
2. Visits those pages (or linked websites), extracts valid email addresses.
3. Produces and submist the final cleaned datasets(CSV).

## 🗂️ Expected Output

<img width="677" height="208" alt="Screenshot_1" src="https://github.com/user-attachments/assets/90e7d628-20aa-4955-9bf0-879b68be78dd" />

## Some of my work and results
- Imported the libraries.
- Got data from each of the 3 pages.
- Made a CSV from each page containing the .html "link" of each industry.
- Merged the 3 CSV files into one.
<img width="527" height="430" alt="Screenshot_2" src="https://github.com/user-attachments/assets/bdc0d49c-c00b-4174-b60f-04ee3528b78c" />

- Used that CSV file to build the whole address of each link: **Standard part** + **variable part**.
- The updated file helped me find the URL's
- |NAME|LINKS| CSV file
<img width="477" height="367" alt="Screenshot_2" src="https://github.com/user-attachments/assets/602d7b3f-cd6f-4a35-8276-b882e1680a10" />


- |NAME|EMAILS|COUNTRY| CSV file
<img width="480" height="495" alt="Screenshot_1" src="https://github.com/user-attachments/assets/d2219e97-a242-4160-bd5c-20b72cdad170" />

## Difficulties
1) Some webpages didn't own a 'Visit Webpage' button so an early approach resulted to having some slots empty in the email CSV.
2) To "route" to different webpages
3) "Green Life Revolution sl" had an email instead of a 'Visit Webpage'. No tests were made.
4) In the end, the tasks required to find the countries too, so I backtracked to make it work.
5) Logic & Code

## References
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
  
