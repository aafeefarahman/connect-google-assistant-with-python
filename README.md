#  Connect-Google-Assistant-with-Python🐍

This is a simple Python project that takes a user question from the terminal, searches it on Google, and prints the direct answer using web scraping.

It uses **requests** and **BeautifulSoup** to fetch and extract the result.

---

##  What this project does❔

* Takes a query from the user
* Sends it to Google search
* Extracts the main answer shown on the page
* Displays the answer in the terminal

---

## Technologies used🛠️ 

* Python
* requests
* BeautifulSoup (bs4)

---

## Requirements

Make sure Python is installed.

Install the required libraries:

```bash
pip install requests beautifulsoup4
```

---

## How to run the program

1. Save the code in a file
   (example: `assistant.py`)

2. Run the file:

```bash
python assistant.py
```

3. Enter your query when asked.

---

## Example 

```text
Enter your query: capital of india
New Delhi
```

Then it asks:

```text
To continue press y:
```

Press `y` to continue searching, or any other key to exit.

---

## Code overview

* `requests` → used to fetch the Google search page
* `BeautifulSoup` → used to parse the HTML
* The result is extracted using the class:

```python
soup.find(class_='Z0LcW XcVN5d')
```

---

##  Important note

* This project depends on Google’s page structure.
* If Google changes its HTML classes, the program may stop working.
* This is only for **learning and academic purposes**.

---

## Key learning points

* How to send HTTP requests in Python
* How to parse HTML using BeautifulSoup
* How to extract specific elements from a webpage
* How to build a simple console-based assistant

---

## Possible improvements

* Add voice input and voice output
* Add better error handling for empty results
* Support multiple result formats instead of only one answer box

---

