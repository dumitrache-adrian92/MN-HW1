Implementation of PageRank in Octave using the faster iterative method, as well as the more accurate algebraic method while also calculating the importance of each page.

PageRank.m takes a file with the following format as input:
```
number of pages
index_of_page number_of_links index_of_links
...
index_of_page number_of_links index_of_links
```
along with a percentage that determines the chance that a user will click on the next page, an error value and outputs the result for the two methods as well as a list of all pages sorted by importance.
