NBA GM Performance Grading Project
==================================

This project provides a robust grading of NBA GMs' performance from 2022-2024. This time frame is because many GMs were not with their current team before then. The analysis includes grades broken out by three categories: signings, trades, and draft picks. These scores are then combined to create a holistic GM performance score. This project examples of data scraping with Beautiful Soup, data cleaning, linear regressions with Scikit-Learn, as well as a model for expected win shares by draft slot.

Summary
-------

This project is broken down into five parts, in which you can find the code for in this repository. The data for this project is a mix of scraping from Basketball Reference for win share data as well as manually creating a transaction data set.

-   Data Scraping Scripts

-   GM Signings Analysis

-   GM Trades Analysis

-   GM Draft Pick Analysis

-   Holistic GM Performance Grading

Below are screenshots of the charts visualizing performance of GMs by each category.

Results - Signings Transactions
--------

For this section, we found the players that signed on new teams between 2022-2024, their contracts, and the win shares they delivered in the year following the acquisition. These were used to determine cost per win shares of each transaction and then aggregated by GM.

![Image](https://github.com/user-attachments/assets/ca1f113d-941c-4405-90ae-1ac7eac49f4f)

Results - Trades Transactions
------

In this section, we built off of the idea of a cost per win share. we divided the cost of win share of players departing in a trade divided by the cost of win share of players acquired in trades. This provided a ratio in which higher values are better for GMs.

![Image](https://github.com/user-attachments/assets/a1a55bb7-2a6b-4457-8747-3e64366b626e)

Results - Draft Picks Transactions
-----------

In this section, we performed a mini project within it by analyzing the win shares produced by every draft pick going back to 2012 for their first three seasons. We then ran a linear regression to smoothen out a curve for expected win shares for each draft slot for their first 1, 2, and 3 years. These values were then used to evaluate the draft picks in the 2022-2024 dataset. 2024 rookies were compared to expected win shares in year 1, 2023 rookies were compared to expected average win shares over their first two years, and 2022 rookies were compared to expected average win shares over their first three years. The main metric of evaluation was the percent change of actual win shares versus expected win shares for each GM in this time frame.

![Image](https://github.com/user-attachments/assets/787536cb-2416-4719-92b3-1c90ca2b43db)

Results - Holistic GM Performance
-----------------------

For the holistic performance, we calculated z scores for each of the three categories then summed up the z scores to create one holistic score. It looks like the overall best GM from this period was Sam Presti of the OKC Thunder.

![Image](https://github.com/user-attachments/assets/cfabf2ab-0dbf-440b-87b1-7f244abe79f5)

Hope you enjoyed reading through this project!

Feel free to contact me with any questions or inquiries.

LinkedIn - <https://www.linkedin.com/in/kevinkietle/>

Email - <kevinkietle@gmail.com>

My portfolio of data analysis projects  can be found at: <https://kevinkietle.github.io/Bootstrap-Website-Portfolio/>
