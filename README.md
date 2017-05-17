# iSelect-ProductMaching-

1. Conversion rates 
	* (call center / Online )
	* top 5 product 
	* by #product recommended 

2. Conversion rates by rankings
   **positive correlated** 


3. Online and call-centre by Sales (histogram , box)
	* x-axis-> sale, y-axis -> customer density 

4. Online and call-centre by customer loyalty (# of services)
	* #total product brought in life-time 
	* x-axis-> # of product brought, y-axis -> customer density  

5. Association rules for Upsales & Cross-sales
	不同组合下，那种组合购买率最高

4. Recommender engine (SVD)

5. linear regression 
	* coefficient (weight) -> p value < 0.05 -> 95% confidence correlated? 
	* price of associated product ( ranking upstream/downstream)

6. provider company  
	* limited information for company and price 
___

1. How effectiveis the iSelect ranking system?
    - Company => measured by conversion rate, ranking / conversion rate (correlation)
    -Customer=> variety of choice ?
2. What are the key differences between the onlineand call-centrechannels?
     - product have higher sales online/phone ?
     - loyalty? # product customer buy => callcentre
     - same product rank which higher?
     - who offer more choice? # of product for each customer
3. Create a metric that can be used for comparing providers and products, and show any interesting differences you find using this metric
    - same provider+product have different value and ranking even for the same customer
    - price+ source + rank
    - intricate relationship
    - price? standard deviation
4. Bonus: Build a predictive model using this data, with the predicted variable being at your discretion.  If you don’t have time to build a model, you can discuss what kind of models could be built and what additional data sources may be required.

