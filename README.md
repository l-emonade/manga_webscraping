## Dataset
Data scraped from https://en.wikipedia.org/wiki/List_of_best-selling_manga. Data is a combination of the first 2 tables on this page, creating a combined table of best selling manga with at least 50 million sales

## Cleaning
Extracted numeric sales values from messy strings like "516 million[a]", turning it into an analyis-friendly integer like 516.

## Visualizations

### Sales Share by Genre
![pie chart sales share genre](/Users/meetshah/Desktop/webscraping/sales_share_by_genre.png)Pie chart comparing sales of genres 

### Top Publishers by Sales
![bar chart publisher sales](/Users/meetshah/Desktop/webscraping/top_publishers_by_sales.png)
Bar chart of the top publishers by total sales.

### Top 20 Manga (colored by genre)
![top 20 manga](/Users/meetshah/Desktop/webscraping/top_20_manga.png)
Bar chart of the top 20 manga, color coded each bar by genre

## Insights 
Shounen manga are overwhelmingly the most popular genre of manga, as seen by both the pie chart and also the top 20 manga. Popular manga like One Piece and Naruto make up the majority of numbers in this genre. In terms of publishers, Shueisha is the clear frontrunner, with more than double the sales of the next highest publisher, Shogakukan. Most sales for these publishers are dominated by Shounen obviously, but some publishers dominate other specific sectors, like how Shogakukan leads the Seinen and Children demographics in sales. 