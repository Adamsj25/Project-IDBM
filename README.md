# Metacritic Movie Data Scraping

This project extracts movie data from Metacritic and stores it in a structured spreadsheet for analysis.

## Goal
Collect movie information and upload the results as an **XLSX, XLS, or CSV** file.

## Data Columns
- Movie Title  
- Release Date  
- Metascore  
- Description  

## Method
- Data is captured using regular expressions.
- All regex patterns used are listed at the top of the spreadsheet or on a separate sheet.

## Notes
Movie thumbnail image URLs are not included.  
They cannot be reliably captured using the same regex approach due to dynamic content loading and inconsistent HTML structure.

## Skills Used
- Regular Expressions (Regex)
- Web Data Extraction
- Data Cleaning
- Spreadsheet Reporting
