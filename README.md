Journal:
Genetics Selection Evolution

Yeer :(1969-2019)
Total =51 Years
Articles: 3143
Language: Python


Programme Description:
Web scraping is done by in python.In this journal each article has a couple of pages in each year.
libraries:Beautiful Soap,Newspaper3k,urrlib,pandas,numpy

Five Functions:

1.(Getting Links)
First Scrapping Useful article links from the webpage:
We used  http urllib  to scrap all the web pages and their links.After generating all the links we need the article’s link which we want to scrap.So we gave condition that filter out the useful article links.we made a dictionary of each year and made a list of all article links that we want to scrap.

 2.(Scrapping 8 Fields)
Main function:
Now we have a links of all articles in the list with their corresponding year dictionary.We have scrap all fields related to articles.In this main function we used Beautiful Soap and Newspaper3k which will take year as a parameter give the Title, Authors, Author Affiliations, Publish Date, Abstract, Keywords, Full Paper (Text format). fields that we want,and store them  in to Dictionary.

3.(Stored Data into Plain Text file elegantly)
Making a DataFrame and  create a text file for each year containing Title, Authors, Author Affiliations,Publish Date, Abstract, Keywords, Full Paper (Text format).

4.(Saving all( DOI.html (e.g.,10.1371/journal.pgen.1005958.html) pages)
Saving all html DOI crawled pages into Folder.In This function make a directory for each year journal and loading all html pages into that respective folder.




5:(Corresponding Author):
There are few articles has a corresponding author and email.This function could take year as a parameter and return a dictionary containing the corresponding Author and email which year has.
