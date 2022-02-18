Google_Search methods are to search through Google to find news articles and collect their links to process with Beautiful Soup or Newspaper3k.  
Google doesn't like robots.  There is a google API and it works relatively well, but it has a hard limit of 100 results.

This script resorts to using the requests package to process a google search.  Google will inhibit your searches when they think you are a robot.  
So care must betaken to not overwhelm the google search engine.  Even with no high volume searches Google still sanctions your searches with robot tests.

The first APi based google script provides a richer opportunity to get metadata about the links from google, but the requests overcomes the limitation of 100 links.  

The requirements of the search engine effort include:
Number | Requirement | Script | Limitation
| :--- | :--- | :--- | :---
1  | Collect search engine urls and metadata | Google API | 100 result limit
2  | Collect urls | google requests | Only URL returned, no metadata

### Google API
Feature | Limitation | Benefit | Mitigation
| :--- | :--- | :--- | :---
google-api-python-client  | Hard limit 10 results per page and 10 pages per search | metadata for urls accessible | perform iterative queries with small time slices

* google-api-python-client
  * requires API account and key
  * requires registration of search engine
      * Limit of results at free level to 100 per day
      * Could scale well in a commercial context
* Bullet list item 2

* Bullet list
   * Nested bullet
    * Sub-nested bullet etc
    * Bullet list item 2
          
### Google requests
Feature | Limitation | Benefit | Mitigation
| :--- | :--- | :--- | :---
direct to 
