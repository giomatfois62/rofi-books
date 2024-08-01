# 📚 rofi-books
eBooks search engine using rofi and libgen.  

### 📦 Installation

Create a python virtual environment and install the requirements.

```bash
# Clone repository
$ git clone "https://github.com/giomatfois62/rofi-books"
$ cd rofi-books

# Create virtual environment & source
$ python -m venv .venv && source .venv/bin/activate

# Install requirements
(.venv) $ pip install -r requirements.txt
```

### 🛠️ Usage

Displays book covers as icons using rofi-next (latest clone from git) and running
```
BOOK_ICONS=1 ./rofi-books.sh
```
The scraper script *scrape_books.py* can be used standalone running
```
./scrape_books.py "book title"
```
![screenshot](https://github.com/giomatfois62/rofi-books/blob/main/screenshot.png)
