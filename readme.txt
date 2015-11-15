Dhoondh : The Ultimate Movie Search
----------------------------------------------------
Technologies Used:
HTML, CSS, Javascript, jQuery, Bootstrap, JSON

Time Taken:
14 hours

API Used:
OMDB API

Overview:
OMDB API curates data from IMDB and RottenTomatoes website and using the API it allows access to those using in JSON/XML format.

Data Response Mode Used: JSON

I have attached a .xlsx file for deeper understanding of different kinds of API calls allowed, data that can be retrived.

Constraints:
1. Max search result set limit = 10
2. Blank search to get all movie title is not allowed.
3. Either Title or IMDB ID has to be supplied

Design Thought Process:
1. Since this is kind of a movie search engine, so I kept it simple like any other search engine design.
2. I allowed 2 different kinds of searches (search by term, title search)
3. Introduced a feature called "Make Me Lucky" which is similar to Google "I m feeling lucky" feature. It actually returns the best matched result. It skips the list of search results page and directly shows the best matched title page.
4. Introduced a feature called "Related Searches" on Title wise display page.

General Info:
1. Website is fully responsive
2. Datas which cannot be retrived for any particular title, those fields are shown N/A

Happy Judging :-)
Search Inception, Godfather to start with