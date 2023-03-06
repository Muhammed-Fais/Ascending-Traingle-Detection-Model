
# SP500 Ascending Triangle Detection

This project aims to develop a small pattern identification model to find Ascending Triangles in the S&P 500 index. The dataset contains over 12,000 bars or candles, with basic information such as the timestamp, open, high, low, and close, for each hour, for two years from January 1, 2021, to December 31, 2022.

### The project consists of three main parts:
1) Data Preprocessing: This involves loading the dataset, checking for missing or NaN values, and resampling the data to the desired frequency.
2) Ascending Triangle Detection: The model detects ascending triangles by identifying a series of higher lows that form an ascending trendline, which intersects with a horizontal resistance line. If an ascending triangle is detected, the model creates a subplot grid and adds the candlestick trace, trendline, horizontal line, and annotations as additional traces to the figure.
3) Pattern Identification: This involves iterating through the windows of data and detecting ascending triangles in each window. If an ascending triangle is detected, the model increments the counter and adds it to the plot.

### Requirements
The following packages are required to run the code:

* pandas 
* numpy 
* plotly

### Usage
To run the program, simply execute the `Ascending Triangle Detection using Model.ipynb` file. This will generate a plot that shows all the Ascending Triangles detected in the dataset, along with a count of the total number of patterns found.

### Results
The program successfully detects Ascending Triangles in the SP500 index, and generates a plot that highlights all the patterns found. The output can be used to gain insights into market trends and potential trading opportunities.

A summary presentation can be found [here](https://github.com/Muhammed-Fais/Ascending-Traingle-Detection-Model/blob/master/Muhammed%20Fais%20-%20Presentation%20for%20Ascending%20Triangle.pptx)

![Output Screenshot](https://github.com/Muhammed-Fais/Ascending-Traingle-Detection-Model/blob/master/Images/triangle%201.JPG)

### Future Work
This project can be extended in several ways, such as:

* Adding more pattern detection algorithms to identify other popular trading patterns.
* Using machine learning techniques to predict future market trends based on historical data.
* Building a web application that allows users to interact with the data and generate custom reports.


## References



* [Plotly Documentation](https://plotly.com/python/)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [NumPy documentation](https://numpy.org/doc/)

