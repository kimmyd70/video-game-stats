#### Data Analysis with Pandas; seattle-401pyn2
### Video Game Sales
- Kim Damalas, 20 Jan 2021
- using stats from [Kaggle](https://www.kaggle.com/gregorut/videogamesales): vgsales.csv


Submission pull request: 


## Description
___________

Taking a tour into Data Science to learn a bit more about the field and tools used in this space
____________
## Feature Tasks and Requirements
___________

Answer the following questions/do the following tasks. Note that the numbers quoted for sales are in the millions, and apply only for those games with over 10,000 sales.:
1. Which company is the most common video game publisher?
2. What’s the most common platform?
3. What about the most common genre?
4. What are the top 20 highest grossing games?
5. For North American video game sales, what’s the median?
    - Provide a secondary output showing ten games surrounding the median sales output
    - Assume that games with same median value are sorted in descending order
6. For the top-selling game of all time, how many standard deviations above/below the mean are its sales for North America?
7. The Nintendo Wii seems to have outdone itself with games. How does its average number of sales compare with all of the other platforms?
8. Come up with 3 more questions that can be answered with this data set.
    - this 
    - this
    - this

______________

## Configuration and Technologies
__________

The user must have Python and all associated dependencies installed.  The project is run inline using a Jupyter notebook
___________
## Changes
__________

20 Jan: files set up; grid coded; first PR
___________

## Testing
________
Testing accomplished using inline testing. The program must pass the provided tests given in the file as well as any custom tests coded by the developer
```
def test():

    def assert_equal(actual,expected):
        assert actual == expected, f"Expected {expected} but got {actual}"

    assert_equal(most_common_publisher, None)
    assert_equal(most_common_platform, None)
    assert_equal(most_common_genre, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[0].Name, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[19].Name, None)
    assert_equal(na_median_sales, None)
    assert_equal(ten_median_na_seller_names, None)
    -- test Q8.1
    -- test Q8.2
    -- test Q8.3

    print("Success!!!")

test()
```
____________

