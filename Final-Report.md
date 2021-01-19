# The Battle of Neighborhoods – Bangalore Edition
# Introduction:
Bangalore, officially known as Bengaluru, is the capital of the Indian state of Karnataka. It has a population of more than 8 million and a metropolitan population of around 11 million, making it the third most populous city and fifth most populous urban agglomeration in India. Bangalore is widely regarded as the "Silicon Valley of India" (or "IT capital of India") because of its role as the nation's leading information technology (IT) exporter. Indian technological organizations are headquartered in the city. A demographically diverse city, Bangalore is the second fastest-growing major metropolis in India. Recent estimates of the metro economy of its urban area have ranked Bangalore either the fourth or fifth-most productive metro area of India.
Owing to the population of Bangalore, transport and the time spent travelling every day is a huge issue today. On average, people spend about 2-2.5 hours in traffic every single day, and a major reason for this traffic is the number of cars on the road. We believe that if public transport were encouraged and the facilities were made more easily accessible, it could drastically cut down the number of personal cars on the road. So with this project, we’re going to analyze the areas that lack a good public transport system. To be precise, we will try to find the top 5 areas that need new bus stations based on the population.
# Data: 
The dataset used contains the following information-
1.	Name of the neighborhoods in Bangalore City
2.	Population of the neighborhood
3.	Average income of the residents living in the neighborhood

The dataset used is from a fellow github user https://github.com.

We will also use foursquare API 'https://api.foursquare.com/v2/venues/explore?&client_id=1DMW4ITPQHBV3UBZ2S2R4UBSVPL0LRFB0HQ2XGW0WCYXF214&client_secret=WKWTVF5N3I5XBVLFFEVI3KJ3HPORSJSEXYK50QCKX5GHCBBO&v=20180605&ll=12.972442,77.58064300000001&radius=1000&limit=1000'

# Approach:
We need to find locations (Neighborhoods) that have a potentially unfulfilled demand for bus stations. Also, we need locations that have a relatively higher population and low average income. We will use the data available to us to find out few most promising neighborhoods that need a new bus station based on this criterion. Advantages of each area will then be clearly expressed so that best possible final location can be chosen by stakeholders.

Technologies used:-

•	IBM Cloud Watson Studio

•	Jupyter notebook

•	Foursquare API

•	Language : Python 3

Packages/Libraries used:-

•	numpy - (to handle data in a vectorized manner)

•	pandas - (for data analysis)

•	json - (to handle JSON files)

•	Nominatim(geopy.geocoders) - (to convert an address into latitude and longitude values)

•	requests - (to handle requests)

•	json_normalize(pandas.io.json) - (to tranform JSON file into a pandas dataframe)

•	Matplotlib and associated plotting modules - (for visualisation)

•	seaborn - (for visualisation)

•	KMeans(sklearn.cluster) - (for K-means clusteing)

•	folium - (for Map visualisation)

# Conclusion: 
After conducting the analysis, we can conclude that the top 5 neighborhoods that need new bus stations are:
1. Kumaraswamy Layout
2. Vasanth Nagar
3. Hulimavu
4. Girinagar
5. HBR Layout
