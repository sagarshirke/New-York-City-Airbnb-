Data Exploration on NYC Airbnb

Airbnb is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking. The company is based in San Francisco, California, United States. The company was conceived after its founders put an air mattress in their living room, effectively turning their apartment into a bed and breakfast, in order to offset the high cost of rent in San Francisco; Airbnb is a shortened version of its original name, AirBedandBreakfast.com.

Database

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more. This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.

Tools & Libraries

• Python • Jupyter Notebook • Pandas • Numpy • Seaborn • Matplotlib • Plotly & Cufflinks

Data Cleaning

I made the following changes and created the following variables:

• The reviews_per_month column containing null values and we can simple put 0 reviews by replacing NAN's

• As, host_names and names are not that important in our analysis, so at least we are good to fill those with some substitutes in both the columns.

• Removed Duplicate Rows

Exploratory Data Analysis (EDA)

• I looked at the different-different trends of the data and Below is a few highlights of the analysis.

• Top Popular Nighbourhood

• Expensive place of living in NYC

• Best Cheapest place of living in NYC

• Top neighbourhoods in NYC with respect to average price/day of Airbnb listings

conclusion

Based on the graph, the most expensive listings tend to entire homes/apartments located in Brooklyn and Manhattan with an average price of 178 USD for entire homes in Brooklyn and an average price of 249 USD for entire homes in Manhattan respectively. This again may suggest that due to the popularity of those boroughs, this influences the price of the listings offered.
