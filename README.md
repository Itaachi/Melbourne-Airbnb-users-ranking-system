First part of the code is web scrapping to get the desired data from web. The scrapping code written scrap the number of reviews listed on the each Melbourne users page on Airbnb website.output was generated as a dataframe with columns url and reviews.The file 'Melbourne Airbnb Reviews.csv' in the repository is the output file for this step.

Second part of the code is to create the desired database containing users urls, number of reviews, their rank and positions based upon reviews. We save this database as a csv file.The file 'Melbourne.csv' in the repository is the output file for this step.

The last part is the function to get desired outputs(Reviews,Position) by providing user url as the input. For this part the csv file created in second part('Melbourne.csv') was used to provide number of reviews and position for each user.
