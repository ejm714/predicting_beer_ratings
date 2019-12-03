# Predicting beer ratings

I scraped Beer Advocate's website and utilized supervised learning models to predict beer ratings with a low complexity, high R-squared random forest regressor.

The best model proved to be a random forest though linear regression did surprisingly well. The fact that linear regression did so well (R-squared of 0.69) makes sense given that the data show people tend to like beers with more alcohol (higher ABV content) and they give higher ratings to more recent beers. More importantly, the average rating of other beers at the brewery seems to be linearly related to the rating of a new beer by that same brewery (see scatterplot below). In short, the brewery is key.

All code is contained is in `notebooks`. Presentation slides are also included in the PDF.

---------

**Languages**: Python, HTML  
**Libraries**: BeautifulSoup, sklearn, pandas, matplotlib, seaborn  
**Methods**: Web scraping, regression  
