# Analyze data from Airbnb
In this project I would like to analyze a data set from Airbnb to find out the main factors to have your room fully booked

# Table of content
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements

# Instalation
Would you please install Anaconda if you haven't yet? You need __gmplot__ to see the map on the explorer, but if you don't, it is ok as the code already handles this part for you. You need to add your google map API key if you want to use the results on the google map.

# Project Motivation
For this project I was interested to use data from Airbnb, data collected from Boston to understand:

1. Which room type is more popular to rent.
2. What rational is behind that.
3. Does price or geographical location affects the occupance of the property?
4. What are the main features that can help to keep your room fully booked?

The commented code for my analysis is available here. If you are interested in applying the code to some other cities, please mind the different features in your data.

# File Descrptions
The .ipynb file is fully commented on and should be self-contained. The first part downloads the data (you might need to change this part if your data is held in a different directory). 

The next part, which is the longest part, preprocesses data to prepare it for analysis. I dropped some features that I felt were unnecessary. Be aware that you might need them for your work.

The third section answers some questions about the data before the data is used to train a learning model to find out the most influential features on room occupancy.

# Results
The main findings of the code can be found at the post available [here](https://medium.com/p/e6cf36853261/edit).

# Licensing, Authors, and Acknowledgements
Must give credit to Airbnb for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/boston/data). Otherwise, feel free to use the code here as you would like!
