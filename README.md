# Sg_house_recommender
Web Scrapping, Machine Learning and Deep learning project

![X-ray image example](https://github.com/ChangeCourse1997/Sg_house_recommender/blob/main/test.png?raw=true)
This is am example of a property listing on https://www.99.co/singapore/sale

## Web scraping

After scraping from the website to obtain all the features of a property like  the listing name, the address code, the number of bedrooms and bathrooms, year built, tenure, property type, mrt distance, squarefeet and price. I will create a model to predict a price base on the several features of the porperty. This will recommend future uses who want to list a property for sale and get an estimate of what price the property should be.

## Model Results on new listings 

For a random new listing on https://www.99.co/singapore/sale/property/tre-residences-condo-KdSQKyUukqS6PAAeSU2JDT?enquiry_position=2&enquiry_source=Search, the actual price listed is $1,580,000 and the model predicted $1,827,183 which is relatively close.


The model was not trained on properties that costs more than 10 million as those few listings will affect the accuracy of the model.Perhaps a separate model for the high end properties could be created and used. More details of data cleaning and model building can be found in Main.ipynb

## Conclusion

Some of the columns I scraped ended up not being used due to the numerous NA values that users did not put when listing their property which I did not account for. The data was also too little to create an accurate model, but the model can still be used to give sellers a rough estimate of the price their porperty should be listed. Given a chance to do things differently I would scrape only the essential data and I would ensure I have a large ebough data source for an accurate model.

Thank you!
