# PriceComparisonPython
Project Title=>Finding price of an item analysing online shopping websites

Introduction=>

Market Analysis and Prediction is the project on technical analysis, visualization using data provided by various companies Used tabulate to get item information, visualized different aspects of it, and finally looked at a few ways of analyzing it and comparing its price.This project makes heavy use of web scraping using Beautiful Soup.

Procedure=>
Step 1:
Web scraping-Scrape the data of various products and their pricing using Beautiful soup .

Step 2: 
Analysis-Collect the data in tables  and compare the prices using Tabulate.

Step 3:
Output-User can identify the website for a particular item according to their requirements.

Input:
Enter the product you want to search for - Wings of Fire

Output:
╒═══════════════════════╤════════════╕
│ Product on Snapdeal   │ Price      │
╞═══════════════════════╪════════════╡
│ Wings of Fire         │ Rs.  260   │
├───────────────────────┼────────────┤
│ Wings of Fire         │ Rs.  1,573 │
├───────────────────────┼────────────┤
│ Wings of Fire         │ Rs.  369   │
╘═══════════════════════╧════════════╛
╒════════════════════════════════════════════════╤═════════╕
│ Products on Amazon                             │   Price │
╞════════════════════════════════════════════════╪═════════╡
│ Wings of Fire: An Autobiography of Abdul Kalam │   223   │
├────────────────────────────────────────────────┼─────────┤
│ The Power of your Subconscious Mind            │   168.8 │
├────────────────────────────────────────────────┼─────────┤
│ Agni Ki Udaan                                  │    75   │
╘════════════════════════════════════════════════╧═════════╛
╒════════════════════════════════════════════════════════════╤═════════╕
│ Product on Flipkart                                        │ Price   │
╞════════════════════════════════════════════════════════════╪═════════╡
│ Wings of Fire: An Autobiography 1st  Edition               │ ₹223    │
├────────────────────────────────────────────────────────────┼─────────┤
│ Wings of Fire (8 Books)                                    │ ₹1,489  │
├────────────────────────────────────────────────────────────┼─────────┤
│ Wings Of Fire: An Autobiography Paperback (English) 1st... │ ₹288    │
╘════════════════════════════════════════════════════════════╧═════════╛
Comparison [('Snapdeal', 223.0), ('Flipkart', 223.0), ('Amazon', 260.0)]

Outcome=>
Analysing prices from different websites of a particular item and finding the best website to buy as per user requirements.
