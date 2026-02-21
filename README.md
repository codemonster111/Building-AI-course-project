# Sales Forecast for E-Commerce Online Shops

Final project for the Building AI course

## Summary

Predicts the number of items sold in an e-commerce online shop within a specified period based on various input variables. Supports in business planning and order management.

## Background

Which problems does your idea solve?
* Provides a more accurate basis for purchasing the right quantity of items per product group/category
* Provides a better basis for general business decisions (planning of sales and storage space, expansion, personnel planning, etc.)
* Prevents over-ordering, transportation costs, inventory management costs, disposal fees, and waste
* Helps optimize budget and free cash flow
* Minimizes dead capital
* Helps optimize pricing and product margins
* Enables improved positioning in purchasing negotiations and risk management
* Increases customer satisfaction

How common or frequent is this problem? 
* Continuousely growing number of e-commerce online shops worldwide
* High return rates, over-ordering, and disposal costs are harmful to the environment

What is your personal motivation?
* In my role as e-commerce shop manager and with a keen personal interest in AI, I see a wide range of potential applications in numerous areas of online business.


## How is it used?

Once started, the tool may forecast the amount per item sold within a specified period of time (e.g. one month) given on the past performance of that item, rival products on the market and in your own shop. It could also highlight potential for new items, marketing campaigns, warn about overstocking or understocking etc.


Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from?

* Internal research (product data feed); (product range, inventory, delivery times, etc.)
* Market research (Google Trends/AI search, social listening); (market share, competing products and pricing, marketing campaigns, etc.)
* Historical product performance (sales, returns, promotions, bundles, etc.)
* Current season (events, holidays)
* Weather forecast
* Customs duties and fees
* Customer structure (new customers/regular customers, Sinus-Milieus®)
* Macroeconomic data (GFK consumer climate, inflation, unemployment rate, wage levels, exchange rates...)

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

* While the tool can assist with planning in purchasing and sales, the results must always be questioned by a “human in the loop.” An insufficient data basis, unforeseen events (black swan events), and other influencing factors can distort the quality of the algorithm.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on?

* Advanced AI knowledge, multilateral cooperation between various departments, and a high-quality database are prerequisites for the success of the project.


## Acknowledgments

* XXXLutz Sverige
* Sinus-Milieus® Deutschland 
* GfK Konsumklima powered by NIM
