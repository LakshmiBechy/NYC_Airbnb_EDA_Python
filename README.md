# NYC Airbnb - Exploratory Data Analysis and Visualization

### Introduction to the dataset: 
   Headquartered in San Francisco, Airbnb is an online platform that enables individuals to rent out their properties for short-term stays. It connects property owners (hosts) with travelers, providing a platform for a diverse range of accommodations, and allowing people to find unique places to stay. This promotes a system where people can share resources and services.This dataset describes the listing activity and metrics in NYC, NY for 2019.

The variables in the dataset are as follows:
- id: Property identification number.
- name: Property name.
- host_id: Host identification number.
- host_name: Host name.
- neighbourhood_group: Boroughs of New york city
- neighbourhood: Specific neighborhoods in each borough
- latitude: Property's latitude coordinate.
- longitude: Property's longitude coordinate.
- room_type: Type of room offered.
- price: cost for the property for a single night
- minimum_nights: Minimum number of nights for which the property has to be booked.
- number_of_reviews: Total reviews received.
- last_review: Date of latest review.
- reviews_per_month: Monthly review count.
- calculated_host_listings_count: Host's listed property count.
- availability_365: Number of days for which the property is available in a year.

### Exploratory Data Analysis (EDA)
The dataset has been thoroughly explored using the process called Exploratory Data Analysis (EDA). The crucial steps are:
- Data cleaning, including duplicate checks, handling missing values, and eliminating outliers.
- Data Analysis - Important numerical parameters have been analyzed and correlations between these variables have also been assessed. Variables such as property price, room types, property availability, minimum nights of stay, reviews, and top hosts have been analyzed both individually and in the context of the five major neighborhood groups: Manhattan, Brooklyn, Queens, Staten Island, and the Bronx.
- Visualization - The insights have been effectively visualized using the Matplotlib and Seaborn libraries.
- Moreover, the wordcloud library has been employed to extract meaningful keywords used by hosts in their property listings.

### Conclusion
- Brooklyn and Manhattan are the most preferred locations as they have maximum number of Airbnb listings in the entire New York city.

- Williamsburg and Bedford-Stuyvesant in Brooklyn borough are found to be the most popular neighbourhoods.

- Average price of properties is found to be maximum in Manhattan (above 140 dollars), which has most number of premium accomodations, followed by Brooklyn (above 100 dollars) when compared to the rest of the city.

- Entire homes or apartments have the maximum share, followed by private rooms. Customer preference for shared rooms in NYC is low.

- Brooklyn, Queens and Bronx have more number of private rooms whereas Manhattan has more number of entire homes or apartments. In all the neighbourhoods entire homes or apartments are expensive compared to private rooms and shared rooms. Except in Manhattan, average price of shared rooms in all other neighbourhood groups are almost the same. Cheapest among all is Bronx.

- Guests prefer entire room or apartments, if they wish to stay for more than a week. Private rooms and shared rooms are preferred for a maximum of 4-5 nights.

- Maximum number of properties which are available almost all throughout the year is found in Staten Island followed by Bronx, which are less populated compared to busiest neighbourhoods like Manhattan and Brooklyn.

- All the top 10 hosts have more than 100 listings, and the top most in the list, have listed more than 300 properties.

- Most reviewed hosts have their properties listed in busiest neighbourhoods.

- Properties listed at a lower price, have received higher number of reviews.

- Manhattan and Brooklyn has the maximum number of listings and therefore have recieved more number of reviews than all the other neighbourhoods.

- Key words in property listing has indicated that most of the hosts have used location-oriented words and adjectives which highlight the comfort of the guest.
