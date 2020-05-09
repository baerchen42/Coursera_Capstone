#### Combine different data analysis method to find out the similarity of cities, based on the cities functionality. The data based on foursquare opensource

# 1 Introduction 
Immigration is the international movement of people to a destination country of which they are not natives or where they do not possess citizenship in order to settle or reside there. As of 2015, the number of international migrants has reached 244 million worldwide. The reason of that could be financial(e.g. wage rates), personal reasons (e.g. family reunification, transnational marriage). 

Barriers to immigration come not only in legal form or political form, but also natural and social form. People when leaving their country also leave their family, friends, social network, and culture. When they arrive in a new country, this is often with many uncertainties including finding work and where to live. To help them ease the migration difficulty, it would be great to help them find a city similar or even better infrastructure and quality of living. 

We can use data science nowadays to achieve that goal. Comparing cities around the world by data, we can find out which are similar, which are different. 






# 2 Business problem 
We’ve often believed that more data is better; however, that actually isn’t true. The rapid rise in collecting data hasn’t been matched by our ability to support, filter and manage the data. Too much data are without enough structure in place to manage and not enough meaningful.  

It is difficult to find the truth behind the data. easy to get lost and with so much information it’s easy to misunderstand what the data is telling you. It would be great if there was a comparison of the different cities in a country of choice which gives you a general view of each place and it’s pro’s and contras. 
Here the problem will be for a family to decide move from Hamburg, the second biggest city in Germany to United State of America.  They want to choose one from the ten biggest cities in USA, which has similar population or more.  (Hamburg has a population around 1841179; the biggest city in USA : New York has 8398748, the tenth is San Jose, which has 1025350). Apart from that, they have their factor list for choosing place to live. 
The requirements are: 
	- Schools , University
	- Hospitals
	- Playground 
	- Shops 
	- Restaurant / Coffee
	- Entertainment
	- Nightlife
	- Lodging
	
The findings of this project would be of interest for families moving from Hamburg to USA, but also for companies choose place to explore new opportunities.

# 3. Methodology

Here we firstly focus on the five most common venue categories of each cities , which is the main characteristics of the city.
Then we use K-Mean clustering method to analyse the diversity. To choose the optimal K value, we will calculate and plot intra-cluster inertia to determine a "elbow" point.

# 4. Conclusion
Combine both method (K-mean and Hierarchical cluster) , which give us precise and same result . That is the  most similar as city 2 (Hamburg) is city 3 (Houston) and 4 (Los Angeles). In respect population, Houston has almost the same as Hamburg, LA has more than double than Hamburg. It could be also a reason for people to choose.  People could also choose another city type (school type) in another cluster group.
Furthermore, we can analyse the difference between Houston, Los Angeles, Hamburg more in detail, which can be studied in the future.
