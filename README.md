# pandas-sales 

Author:  Erin James Wills, ejw.data@gmail.com  

![Analysis of Purchasing Data](./images/sales-pandas.png)  
<cite>Photo by [Clay Banks](https://unsplash.com/@claybanks?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/sales?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)</cite>

<br>

## Overview
<hr>
The dataset and notebook investigate the sales of add-on features and enhancements for a free-to-play video game.  The purchase of these items is optional but are encouraged and provide advantages to the players.  Since I will be analyzing the purchases, I will refer to the players synomously as the purchaser.  

<br>

## Technologies  
*  Python
*  Pandas

<br>


## Data Source  
Dataset generated by Trilogy Education Services. Origins beyond this is unknown. 

<br>

## Setup and Installation  
1. Environment needs the following:  
    *  Python 3.6+  
    *  Pandas  
1. Activate your environment
1. Clone the repo to your local machine
1. Start Jupyter Notebook within the environment from the repo
1. Run `purchase_analysis.ipynb` 

<br>

## Analysis  

The basic analsys shows:
*  There are 576 purchasers with 162 of them making more than one purchase.  The breakdown of purchasers with multiple purchases is such:  
   *  5+ purchases:  1 person
   *  4  purchases:  2 people
   *  3  purchases:  35 ...
   *  2  purchases:  124 ...  
*  Those repeat purchasers made a total of 366 purchases.  
*  There were a total of 780 purchases with 183 items being unique.  
*  The average price was $3.05 per item and generated a total revenue of $2,379.77.  
*  Of the 576 purchasers, 84% are male (481) and 14% are female (81).
*  Males spend the least on average per purchase ($3.02) while females spend close to $3.20 per purchase.  Considering repeat purchases, the average sales to males is $4.07 and to females is $4.47.  Remember, that most sales are single purchases.  
*  The demographic that represents 47% of the total purchases is the 20-24 year old group.  This group has more than double the purchases than the next best group which is the 15 to 19 year old group.  
*  When looking at the total revenue by age group, very similar trends exist compared to Total Purchases.    This may suggest that the prices are very similar for all products.  
* The average price of purchases by age groups is between $2.90 and $3.60 across all age ranges.  The number of repeat purchasers by age group is fairly siimilar with 30-34 year olds having a similar repurchase rate as 20-25 year olds but just at 20% the volume.  
*  Top purchasers (top 5 based on total expenditures) typically had 3-5 purchases and $13-$19 spent on the game.  


<br>