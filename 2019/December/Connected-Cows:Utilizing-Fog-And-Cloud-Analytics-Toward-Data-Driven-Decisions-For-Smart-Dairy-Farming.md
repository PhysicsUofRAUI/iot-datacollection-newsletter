# Reference
Taneja, Mohit, et al. "Connected cows: Utilizing fog and cloud analytics toward data-driven decisions for smart dairy farming." IEEE Internet of Things Magazine 2.4 (2019): 32-37.

# PDF Link
https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8982746

# Technologies
- [Fog Computing](https://en.wikipedia.org/wiki/Fog_computing)
- [K-nearest neighbors](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)

# Overview
A herd of 150 cattle were monitored with an off the shelf ankle monitor that transmitted the data to a laptop that was already availble at the test farm. The data was collected and the fog node (the farmers laptop) coverted that raw data to three parameters lying time, step count, and swaps. The processed data was then sent to the cloud to be accessed and assesed by the farmer. Three different machine learning algorithms were used to further analyze the data K-nearest neighbors, support vector machines, random forest, and decisions trees. In the end the authors used the K-NN algorithm because it had the best outcome of the 4 tested. 

When the paper was published the authors planned further deployments which, if they went through with it, would be active right now. It is part of the [IoF2020 project](https://www.iof2020.eu/), and would result in around 1000 head of cattle being monitored. 
