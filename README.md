Comparative sentiment analysis of various news outlets

#### Descriptions of the files:

#### 20180516-20180621_reuters_unique.csv:
Unique Reuters articles and their associated attributes for the given date range. All distance calculations are made using the contents this file. 

#### nyt_uniques_topicsLabeled.csv: 
Unique NYT articles with labeled sections. They were published in the same date range as the Reuters articles were. All distances calculations are made using the contents of this file. 

#### reuters_titles_first10000.pkl:
Titles for the first 10000 Reuters articles 

#### reuters_titles_rest.pkl:
titles for the rest of the Reuters articles 

#### Title_Distances_121018_1.ipynb: 
Code to calculate the cosine distances between the titles of the 1400 NYT and 22322 Reuters articles. Produces the “title_distances.pkl” file as a result. 

#### Article_Distances_103018.ipynb:
Code to calculate the cosine distances between 1400 NYT and 22322 Reuters articles

#### Keyword_Distances_141018.ipynb:
Code to calculate the cosine distances between 1400 NYT and 22322 Reuters article keywords. 

#### Checking_Close_Articles.ipynb:
Code to get the NYT and Reuters article pairs with n=10 using big_df

#### close_articles_df1.csv:
Contains pairs of NYT and Reuters articles with n=10

#### Get_Titles_for_Reuters.ipynb:
Code to get the titles for the Reuters articles and store them in pickled files.

#### NYT_Scraper_All_Articles.ipynb:
Code to get the NYT articles and their associated attributes 

#### Reuters_Scraper_All_Articles.ipynb:
Code to get the Reuters articles and all associated attributes (except for their titles. Get_Titles_for_Reuters.ipynb takes care of that part)



