#### Question/need:

* Postmates is a quick-commerce and food delivery service company based in San Francisco. The company offers local delivery of food and other online purchased goods. And many customers who used to use Postmates complained that their orders always got delayed or the tracking were inconsistent most of the time (https://www.grubstreet.com/2017/02/best-food-delivery-nyc-ranking.html).

In this analysis, I'm analyze Postmates order delivery durations in New York in following stages:

 * time between order received and order picked up
 * time of preparing the order
 * time between order picked up and order dropped off

and identify the areas that postmates could save more time in order to improve delivery efficiencies.


* Who benefits from exploring this question or building this model/system?
 Postmates will benefit from exploring their order delay issues. By figuring out the root cause of delay, Postmates could consider to apply linear regressions or time series analysis to forecasting the order volume especially during the peak time.

#### Data Description:
* I'll mainly use a Postmate transaction data which I found on [Kaggle](https://www.kaggle.com/), and combine with some Geo datasets I found on [Zip Data Map](https://www.zipdatamaps.com).

* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
The unit of analysis in the dataset is each unique transaction. The features include:

* order_id
* customer_id
* courier_id
* num_items
* restaurant_category
* item_category
* ordering_timestamp/ timestamp_courier_started/ timestamp_courier_arrived_pickup/ timestamp_courier_left_pickup/    timestamp_courier_arrived_drpoff
* latitude and longitude of the pick-up and drop-off locations
* courier_vehicle_type

#### Tools:
* How do you intend to meet the tools requirement of the project?
I'll mainly use Google Sheet for data manipulation and Tableau for visualization.

* Are you planning in advance to need or use additional tools beyond those required?
I may need Python to do some data manipulation work.

#### MVP Goal:
* I'll deliver a preliminary analysis and a data science proposal for Postmates.
