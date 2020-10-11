Project Brief

You work for a company 'X', an asset management company. 'X' wants to make investments in a few companies. The CEO of 'X' wants to understand the global 
trends in investments so that she can take the investment decisions effectively.

Business and Data Understanding

'X' has two minor constraints for investments:
1. It wants to invest between 5 to 15 million USD per round of investment
2. It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in
* For your analysis, consider a country to be English speaking only if English is one of the official languages in that country

Before getting to specific questions, let’s understand the problem and the data first.

1. What is the strategy?

'X' wants to invest where most other investors are investing. This pattern is
often observed among early stage startup investors.

2. Where did we get the data from?

I have taken real investment data from crunchbase.com, so the insights I get may be incredibly useful. For this project, I have divided the data into the following files:
We have to use three main data tables for the entire analysis

3. What is X’s business objective?

The business objectives and goals of data analysis are pretty straightforward.
 
  1. Business objective: The objective is to identify the best sectors, countries,and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

  2. Goals of data analysis: Our goals are divided into three sub-goals:
  
○ Investment type analysis: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Teclov can choose the type that is best suited for their strategy.

○ Country analysis: Identifying the countries which have been the most heavily invested in the past. These will be 'X' favourites as well.

○ Sector analysis: Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, we will need to map each sub-sector to its main sector.)
  
  1. Company details
companies: A table with basic data of companies
  
  2. Sector Classification:
mapping.csv: This file maps the numerous category names in the companies table(such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The purpose is to simplify the analysis into eight sector buckets, rather than trying toanalyse hundreds of them.
