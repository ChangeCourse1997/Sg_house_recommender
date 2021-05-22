# Sg_house_recommender
Web Scrapping, Machine Learning and Deep learning project

![X-ray image example](https://github.com/ChangeCourse1997/Sg_house_recommender/blob/main/test.png?raw=true)
This is am example of a property listing on https://www.99.co/singapore/sale

## Web scraping

After scraping from the website to obtain all the features of a property like  the listing name, the address code, the number of bedrooms and bathrooms, year built, tenure, property type, mrt distance, squarefeet and price. I will create a model to predict a price base on the several features of the porperty. This will recommend future uses who want to list a property for sale and get an estimate of what price the property should be.

## Model Results on new listings 

For a random new listing on https://www.99.co/singapore/sale/property/rv-residences-condo-sBf7kkEtUiAa7qW9FqBdpa?enquiry_position=18&enquiry_source=Search, the actual price listed is $1,790,000 and the model predicted $1,626,160.9 which is quite close

For another random new listing taken a week later from https://www.99.co/singapore/sale/property/475a-upper-serangoon-crescent-hdb-tMsHKYePMNP45oNPRHzBqF?enquiry_position=1&enquiry_source=Search, the actual price of the listing is $840,000 and the model predicted $711,213.1 which is also quite close. 

The model was not trained on properties that costs more than 10 million, so let's test it out on a new listing https://www.99.co/singapore/sale/property/fernhill-crescent-landed-9pfjgw9AhbiWaZGtLzCe2n?enquiry_position=3&enquiry_source=Search. The actual price listed is $15,000,000 and the model predicted $10,831,639 which is quite far off as the model was not trained on expensive property. Perhaps a separate model for the high end properties could be created and used.

More details of data cleaning and model building can be found in Main.ipynb

Thank you!
