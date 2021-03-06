# Ranobes Scraper

This Python script scrapes novels from [Ranobes](https://ranobes.net/) and saves them into .epub format with an optional conversion into .pdf format

### Features

- Regular updates
- No 'In preparation, Keguan...' for chapters
- 10,000+ novels to scrape
- Terminal based and simple to use
- Scraping progress can be monitored

### Getting Started

Install the latest version of [Python](https://www.python.org/). It may work with older versions but has not been tested.

### Prerequisites

This script depends on bs4, ebooklib, progress and pdfkit. To install these navigate to the project folder and run

```
pip install -r requirements.txt
```

### Usage

Navigate to the project folder and run

```
python main.py
```
to start the script

Now copy and paste the URL of the novel you wish to scrape from [Ranobes](https://ranobes.net/).

<img src = "images/Demo/novel_webpage.PNG" alt = "novel_webpage">


It will start extracting the chapter list.

<img src = "images/Demo/extract_index.PNG" alt = "extract_index">


After that, select the chapter range and it will start scraping the chapters.

<img src = "images/Demo/chapter_range.PNG" alt = "chapter_range">


Now save the file. The file gets saved in .epub format

<img src = "images/Demo/save_file.PNG" alt = "save_file">


Enjoy your read!


### Lithium: EPUB Reader

Personally, I prefer the [Lithium: EPUB Reader](https://play.google.com/store/apps/details?id=com.faultexception.reader) due to its simplicity and ease of use to read .epub files.

<table>
    <tr>
        <td><img src = "images/Lithium/lithium_1.png" height = 400 width = 180 alt = "lithium_1"></td>
        <td><img src = "images/Lithium/lithium_2.png" height = 400 width = 180 alt = "lithium_2"></td>
        <td><img src = "images/Lithium/lithium_3.png" height = 400 width = 180 alt = "lithium_3"></td>
        <td><img src = "images/Lithium/lithium_4.png" height = 400 width = 180 alt = "lithium_4"></td>
    </tr>
</table>

### Finally

Feel free to open an issue if you face any bugs or have any suggestions.
