# HoneywellProject
 
> Python pipeline that reads an Excel document registry, scrapes a target website using Playwright, and validates each record's existence, reference number, and publisher — outputting a confidence-scored Excel report.
 
---
 
## Overview
 
Manually verifying hundreds of documents against a website is slow, repetitive, and error-prone. This project automates that entire process.
 
The system takes an Excel file containing document records, searches for each document on a target website, extracts key metadata, and produces a structured validation report — in minutes, not hours.
 
For each document, the system answers three questions:
 
- Does the document **exist** on the website?
- Does the **reference number** match what is in the Excel file?
- Does the **publisher** match the expected value?
---
 
## Tech Stack
 
| Component | Technology |
|---|---|
| Language | Python 3.10+ |
| Excel I/O | pandas, openpyxl |
| Web Scraping | Playwright (Python) |
| Fuzzy Matching | python-Levenshtein / difflib |
 
---
