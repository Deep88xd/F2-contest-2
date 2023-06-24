# F2-contest-2

# User Interface
![image](https://github.com/Deep88xd/F2-contest-2/assets/98728227/21c45714-5221-4839-b553-6f6cecf9f48b)


# Fetch data from an API using .then and async/await

1. The link for the GET api is https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=10&page=1&sparkline=false
2. This will return an array of 10 objects, each containing a name,id,image,symbol, current_price,total_volume
3. Render all of them in the form of a table as given in the UI.
4. Handle the promise using both methods, .then and using async await.
5. Create a search button which allows the user to search and filter the data based on the input.
6. Create a sort button which allows the user to sort the data based on market cap and percentage change.

# Rendering data in a table
1. Creation of a table structure using HTML
2. Proper inclusion of table headers
3. Iterating over the data array and dynamically populating the table rows and cells with the retrieved data

# Search functionality
1. Proper implementation of the search functionality to filter the data based on user input
2. Dynamic rendering of the filtered data in the table

# Sort buttons for market cap and percentage change
1. Proper implementation of buttons to sort the data by market cap
2. Proper implementation of buttons to sort the data by percentage change
