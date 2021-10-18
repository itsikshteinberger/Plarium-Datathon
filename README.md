# Plarium Datathon
<br/>
<p align="center">
<img src="https://www.import.io/wp-content/uploads/2019/09/data-analysis-blog.jpg" alt="drawing" width="700"/>
</p>
<br/>

__"At the end of April 2020, we've noticed a drop in our company's profit. About 2 weeks later, we've detected a sharp drop in Retention rates. <br/>
A smaller share of players continued to play beyond the first day of downloading our game..."__ <br/><br/>
The objective of this analysis is to try and identify the source or cause of these changes in our metrics and provide suggestions for recovery.
<br/><br/>
__[Dataset](https://github.com/itsikshteinberger/Plarium-Datathon/blob/master/Plarium_Dataset.csv) includes:__
* Date
* Country (top 11 countries and all others under "Rest of the world")
* Affiliates (top 11 affiliates and "Rest")
* Regs the number of players who've downloaded our game and started playing
* Ret_Day1 the number of players who've returned on the next day to play again
* Ret_Day7 the number of players who've returned 7 days later to play again
* Spend the total sum we've invested in marketing activity
* Depositors_DX (Day0, Day1, Day7, Day10 and Day30) the number of players who've purchased at least 1 item with real money, in our game (this is an accumulative number so for instance Day10 includes all depositors of the first 10 days)
* Deposits_DX the number of purchases of items with real money, in our game (this is an accumulative number as well)
* Deposit_Amount_DX the sum of real money used by players in our game (this is an accumulative number as well)
<br/><br/>
## Results
The detailed business report can be found [here](https://github.com/itsikshteinberger/Plarium-Datathon/blob/master/Tableau/Report.pdf).<br/>
You can find the notebook for cleaning the data and some analysis [here](https://github.com/itsikshteinberger/Plarium-Datathon/blob/master/Datathon.ipynb).
## Tools I used
* Pandas
* Matplotlib
* Seaborn
* Tableau
<br/>
<img src="https://company.plarium.com/images/press-kits-undersea-solitaire-2.png" alt="drawing" width="200"/>

> Plarium logo
