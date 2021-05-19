#### Question/need:

* Since the pandemic food delivery apps become more importamt to both customers and restaurants. Grubhub dominated the majority of the market as of 2020, and its market share was 53%, then followed by Uber Eats(24%) and Doordash(21%), Postmates only accounted for 2% of the market (before merged into Uber Eats). And many customers who used to use Postmates complained that their orders always got delayed or the tracking were inconsistent most of the time (https://www.grubstreet.com/2017/02/best-food-delivery-nyc-ranking.html).

In this analysis, I'm trying to compare the order delivery durations between Doordash and Postmates. And also try
understand what is the major factor(s) that likely causes order delays in Postmates.

* Who benefits from exploring this question or building this model/system?
 Postmates will benefit from exploring their order delay issues. By figuring out the root cause of delay, an analytic solution will be generated to help decrease the number of delay orders.

#### Data Description:
* I'll mainly use a Postmate transaction data and a Doordash transaction data which I found on [Kaggle](https://www.kaggle.com/), and combine with some Geo datasets I found on [Zip Data Map](https://www.zipdatamaps.com) 

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
* I'll deliver a preliminary analysis of comparing order delivery efficiencies between Doordash and Postates as the MVP.
