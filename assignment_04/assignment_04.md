Attached Files:
File xml_containing_html.xml.zip (47.042 KB)

Attached a compressed XML file. Some of the fields contain HTML. ​

1. Extract the XML from the .zip file. In Python, use a module to parse the XML (do not write an XML parser)​
2. Using Python, extract the HTML from the XML. Then use BeautifulSoup4 to parse the HTML 
3. For each HTML page, report the number of links (URLs with the tag < a href="URL">text) in each HTML page 
4. Submit a single Jupyter notebook that parses the XML file and produces the count of links per HTML file.​

Advanced students: if you complete the assignment above and are are seeking a challenge, use an alternative method (i.e., regular expressions or Python's find) to validate the count of HTML links per page reported by BeautifulSoup4
