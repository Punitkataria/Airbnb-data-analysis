# Analyzing Airbnb's data 

**This is an analysis from Boston and Seattle's Airbnb data. The project's objective was to answer 3 questions using data analysis and modelling techniques. 

### Table of Contents
1. [Used Frameworks](#frameworks)
2. [Motivations](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)

### Used Frameworks <a name="frameworks"></a>
The project was implemented with Anaconda's distribution of Python 3.9. The used frameworks are the following:
1. Pandas
2. NumPy
3. Matplotlib 
4. Seaborn
5. String 
6. Warnings
7. Scikit-Learn 

### Project Motivation<a name="motivation"></a>
After taking a look at the data, I wanted to to understand what are the main variables that can affect your listing's price and review scores. I also wanted to compare Seattle's listings with Boston's in order to check if there was a overall better city when it comes to Airbnb listings. The three questions were:

1. Which city has the best listings? Which one has more expensive ones? Is there a connection in that?
2. What's the connection between price and occupation rate? Where does the quality of the listing fits in that?
3. What are the main features that influences the review rates? What about the prices?

### Results<a name="results"></a>

**Which city has the best listings? Which one has more expensive ones? Is there a conection in that?**

- After looking at the data, it got clear that the city of **Seattle has the best listings**. It not only has a **higher average review rating**, 78.8 compared with 72.1 in Boston, but it also has a much higher positive/negative review ratio, 55.4 compared with 31.9 in Boston. In addition to that, **Boston has a much higher average price**, 168.70 dollars compared with 127.02 dollars in Seattle. That means that more expensive houses are not necessarily better. 
- In my opinion, when people get into more expensive houses they tend to be more demanding. In that case, sometimes it leads to people geting disapointed with the listing, leading to negative reviews. 

#### What's the connection between price and occupation rate? Where does the quality of the listing fits in that?

- The correlation between price and occupation rate is not very strong. That means that lowering the price of your house won't necessarily call for more attention.
- One interesting finding is that expensive houses (above 400 dollars) tend to have either a very high or very low occupation rate. 

#### What are the main features that influence the review rates? What about the prices?

### Review Rates:
- The most important features when predicting an Airbnb listing review score is the price followed by the occupation rate and the number of good and bad reviews. **That actually makes a lot of sense**. 
    - People will evaluate your house based on the price you put on it. If you charge too much, people will probably be disappointed and review it poorly. 
- Other important indicator is the **cleaning fee**.
    - Apperently people dont' like to spend a lot when it's time to clean. Quite interesting. 
    
### Listing Prices:
- The most important features when predicting the price of a listing are:
    1. The **cleaning fee**: When it's very expensive to clean a house, the house must be very expensive as well
    2. The **number of bedrooms**: More bedrooms -> bigger house -> more expensive house. Makes Sense.
    3. The **number of people it accommodates**: More people -> more bedrooms -> bigger house -> more expensive house. Makes Sense.


### File Descriptions<a name='files'></a>

- There are two data folders: 'Seattle' and 'Boston'. In there you can find the 6 datasets. 
- The jupyter notebook contains the entire project code that follows the CRISP-DM process, as well as markdown cells for documentation. 

### Acknowledgements<a name="acknowledgements"></a>
- Boston's data can be found here: https://www.kaggle.com/datasets/airbnb/boston 
- Seattle's data can be found here: https://www.kaggle.com/datasets/airbnb/seattle
- Feature Importance Analysis: https://towardsdatascience.com/explaining-feature-importance-by-example-of-a-random-forest-d9166011959e
- Hyperparameter Tuning: https://towardsdatascience.com/gridsearchcv-or-randomsearchcv-5aa4acf5348c



