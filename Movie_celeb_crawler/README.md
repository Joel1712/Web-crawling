# Movie_celeb_crawler
Crawl popular websites &amp; create a database of Indian movie celebrities with their images and personality traits

[**Movie_celeb_imdb.csv**](https://github.com/Joel144/Movie_celeb_crawler/blob/master/Movie_celeb_imdb.csv)  Contains data of top 200 (based on IMDB criterion) indian actors collected from IMDB sites 

[**Movie_celeb_wiki_full.csv**](https://github.com/Joel144/Movie_celeb_crawler/blob/master/Movie_celeb_wiki_full.csv)  Contains data of indian actors from wikipedia pages.This is a bigger database but quality of data in terms of accuracy and content is lower than IMDB dataset.

**_Note:_** Since there was an issue of connection request response from host (due to large number of rrequests placed) the the code was executed to generate list of actors and actresses separately and both lists were manually combined.Although IP rotation could have solved the issue , lack of resources prompted me to resort to this method

[**Movie_celeb_IMDB.ipynb**](https://github.com/Joel144/Movie_celeb_crawler/blob/master/Movie_celeb_IMDB.ipynb)  Jupyter notebook used for data extraction from IMDB pages

[**Movie_celeb_wiki.ipynb**](https://github.com/Joel144/Movie_celeb_crawler/blob/master/Movie_celeb_wiki.ipynb)  Jupyter notebook used for data extraction from wikipedia pages
