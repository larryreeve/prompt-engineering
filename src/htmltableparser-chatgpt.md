# HTML Table Parser - ChatGPT


**Prompt:**
```
write python code that extracts data from a html table using only standard python libraries 
```

**Response:**
```
import urllib.request
from html.parser import HTMLParser
import csv

# Define the URL of the webpage containing the HTML table
url = 'https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal)'

# Send an HTTP request to the URL and read the response
response = urllib.request.urlopen(url)
html = response.read()

# Define an HTML parser to extract data from the table
class TableParser(HTMLParser):
    def __init__(self):
        super().__init__()
        self.in_table = False
        self.in_header = False
        self.in_row = False
        self.data = []
        self.current_row = []

    def handle_starttag(self, tag, attrs):
        if tag == 'table' and ('class', 'wikitable sortable') in attrs:
            self.in_table = True
        elif self.in_table and tag == 'th':
            self.in_header = True
        elif self.in_table and tag == 'tr':
            self.in_row = True
            self.current_row = []

    def handle_endtag(self, tag):
        if self.in_table and tag == 'table':
            self.in_table = False
        elif self.in_table and self.in_header and tag == 'th':
            self.in_header = False
        elif self.in_table and self.in_row and tag == 'tr':
            self.in_row = False
            self.data.append(self.current_row)

    def handle_data(self, data):
        if self.in_header:
            self.current_row.append(data.strip())
        elif self.in_row:
            self.current_row.append(data.strip())

# Parse the HTML content using the custom parser
parser = TableParser()
parser.feed(html.decode('utf-8'))

# Write the extracted data to a CSV file
with open('gdp_data.csv', 'w', newline='') as file:
    writer = csv.writer(file)
    writer.writerow(parser.data[0])
    writer.writerows(parser.data[1:])
```
