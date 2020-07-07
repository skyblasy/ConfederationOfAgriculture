## Confederation of Agrigculture and Livestock Brazil Data Science Project
### By Schuyler Blasy
#### How are agricultural export products to China and Africa performing over time?

The Confederation of Agriculure and Livestock Brazil is an agricultural loby representing Brazilian farmers. Their interest and goals of the projects are to know how classes of products are performing with respect to each other over time for the given markets of China and the regional market of Africa. Using Scipy's dendogram, I was able to create a hierarchy of how the products are related with their given time series. Going beyond that and understanding different dimmensions of how these products are similar/disimliar to each other required using Kmeans clustering. Kmeans, in intself, cannot accept a time series, but transforming the series as a linear trend and culmulative totals allowed for creating new dimmensions to group on. 
