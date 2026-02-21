# Sales Forecast for E-Commerce Online Shops

Final project for the Building AI course

## Summary

Predicts the number of items sold in an e-commerce online shop within a specified period based on various input variables.

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
* In my role as e-commerce manager, my colleagues and I face this problem every day. How can we purchase the perfect quantity of items and satisfy customers by selling them at a fair price?


## How is it used?

The tool may forecast the amount per item sold within a specified period of time (e.g. one month) given on the past performance of that item, rival products on the market and in your own shop. It could also highlight potential for new items, marketing campaigns, warn about overstocking or understocking etc.


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

* Internal research (Product data Feed); (assortment, stock level, delivery time...)
* Market reserach (Google/AI search); (market share, rival products and pricing, marketing campaigns...)
* Historical item performance (sales, returns, promotions, bundles...)
* Actual Season
* Weather prediction
* Customs duties and fees
* Customer structure (New customers/repeat customers, Sinus-Milieus®)
* Macroeconomic data (GFK-Konsumklima, inflation, unemployment rate, Wage levels, exchange rates...)

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
