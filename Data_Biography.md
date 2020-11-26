# Data Biography

## Student Number: XXXXXXX

---

### 1. Who collected the data?

_Inside Airbnb, an independent, non-commercial project which was brought to us by Murray Cox collected the data. Many other people are involved in the project._

---

### 2. Why did they collect it?

_Airbnb is a popular house sharing platform. By collecting data, people can see how Airbnb is being used to compete with the residential housing market._

_Airbnb also have impacts on many social and economic issues in cities. They hope to use the data to answer some questions related with Airbnb._

---

### 3. How was it collected?

_The data utilizes public information complied from the Airbnb website including the availability calendar for 365 days in the future, and the reviews for each listing._

_Data is verified, cleansed, analysed and aggregated._

_Neighbourhood names are cleansed and compiled by comparing the listing's geographic coordinates with a city's definition of neighbourhoods. Airbnb neighbourhood names are not used because of their inaccuracies._

---

### 4. What useful information does it contain?

_1. Information of Host_

_This part of information includes name,hosting time,host location,self-description, response rate and acceptance rate, whether the host a superhost, picture, count of different types of listings and verification information of host._

_2. Information of the flat_

_Including the location, property type, room type, accommodations, bathrooms, bedrooms, beds and amenities._

_3. Information of rent_

_Price, minimum nights, maximum nights and availability for different periods.__

_4. Information of reviews_

_Number of reviews of different periods, reviews per month, first review time, last review time, and review score of different aspects._

---

### 5. What useful information is it missing?


_Host response rate is the percentage of new queries and reservation requests hosts responded to, not including the rate hosts responded to reviews._


_Many fields of information provided by the hosts, such as name, location, picture and the flat information cannot be verified and true information may be missing._

---

### 6. To what extent is the data 'complete'?

_This dataset includes many useful information related with host, flat, rent and consumers' reviews. These information are rather fundamental and can be used for some basic studies. However, some critical information is still missing._

_1. The comments of reviews_

_This makes it impossible for us to study the feelings of consumers._

_2. Time series data such as the daily price of each flat._

_This dataset only includes the average price in the last 14 days without the detailed time series data._

_3. Landlord of the flat_

_4. Target guests of the flat_

_It is impossible to determine whether the listings are available for short-term holiday renting or just conventional bed and breakfast accommodations._

_5. House rules such as whether the host allows pets, parties or smoking._

_6. Information of guests_

_Finally, sometimes Airbnb may remove and hide some unwanted listings which makes information incomplete and biased._

---

### 7. What kinds of analysis would this support?

_1. Analysis based on price._

* We can study how host’s and the product’s attributes affect the consumers' choices.
* We can study the differences of Airbnb prices between different areas.
* We can compare Airbnb’s price with other housing actors.
_2. Analysis based on consumer experience. We can study how host’s and the product’s attributes affect consumers’ choices and review scores._

_3. Analysis based on the location of the flats._

* We can study the spatial pattern of Airbnb in different areas in UK.
* We can study spatial correlation between Airbnb flats.
* We can study what are the determinants of Airbnb location in different areas in UK. For instance, if there are more Airbnb listings in the areas with more tourists.

_4. Impact of Airbnb on local housing markets._

---

### 8. What kinds of analysis would it _not_ support?

_1. Deep study of user experiences. It is impossible to study consumers’ sentiments and find out how users evaluate their experience and what they really care about._

_2. Relation between hosts and guests.We cannot study how hosts and guests judge each other by their gender, race and other characters, which is the digital discrimination._

_3. Preferences of different types of consumers._

_4. Analysis about whether Airbnb is a kind of sharing economy and how it affect the local communities._


---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

_When we use the data from Airbnb or other datasets, although Inside Airbnb uses the public information complied from the Airbnb website, the ethical issues occur inevitably since both the hosts and guests are not well informed about the use of their data._

_Thus, I will firstly list what data used in above-mentioned studies are sensitive and then justify the ethics of these analysis._

_1. Text messages_

_When we want to deeply explore the attributes of the hosts and consumers, we need to do text analysis for their self-description or reviews. However, people who sent these text messages did not consent to our particular use(crisis data). So this is not ethical.

_2. Photos_

_We hope to analysis whether the picture of a host can contribute to the trustworthiness with guests, however, this is the privacy of the host even if the picture is published publicly. _

_3. Other personal information_

_From the pictures of hosts, we can collect data about their gender and race. However, these are all privacy information of people, and it is not ethical to use them._

_4. Geodata_

_We need to use the location information of flat to do spatial analysis.  We do use the location data but we don’t use the specific name of each flat since the neighbourhood names are cleansed and compiled by comparing the listing's geographic coordinates. Also, the studies don’t focus on the location of specific flat, but the special pattern of all Airbnb flats in the area. So I think these studies are ethical._

_Finally, I think the studies involves the picture, gender, race and texts of people are not ethical enough. Analysis based on price not exploring the privacy of hosts,  analysis based on location of flats, and analysis about the impact of Airbnb on housing markets are ethnical.


### References:

[1]      1. K. Crawford, M. Finn, "The limits of crisis data: analytical and ethical challenges of using social and mobile data to understand disasters," GeoJournal, vol.80, pp.491–502, Nov 2014.
