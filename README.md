## Confederation of Agrigculture and Livestock Brazil Data Science Project
### By Schuyler Blasy
#### How are agricultural export products to China and Africa performing over time?

The Confederation of Agriculture and Livestock Brazil is an agricultural lobby representing Brazilian farmers. Their interest and goals of the projects are to know how classes of products are performing with respect to each other over time for the given markets of China and the regional market of Africa. Using Scipy's dendrogram, I was able to create a hierarchy of how the products are related with their given time series. Going beyond that and understanding different dimensions of how these products are similar/dissimilar to each other required using Kmeans clustering. Kmeans, in itself, cannot accept a time series, but transforming the series as a linear trend and cumulative totals allowed for creating new dimensions to group on. I also performed a simple time series and rolling average for various exports in the China market.
