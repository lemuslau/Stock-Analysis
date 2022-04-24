# Stock-Analysis
Background:

Steve loves having the ability to analyze entire datasets at the click of a button, but was having difficulty looking at several years’ worth of data without having to wait long periods of time for the analysis to be executed by the Visual Basics tool (VBA) I created. The purpose of this analysis is to allow Steven to run a dataset of hundreds to thousands of stocks without long periods of idle time so that he can make the best decisions quickly based of trends in total daily volume and yearly returns for each stock.

Results

In this analysis I had previously created a “yearValue” Macro in combination with a “All Stocks Analysis” to run the data for the years 2017 and 2018. From this Macro the information that populated took 1.41 seconds to execute for 2018 and 1.42 seconds for 2017. Using a refactored code I was able to adjust my code to reduce the run time by half. The results were that the All Stock Analysis for the year Value inputs now allowed the 2018 dataset to run in .31 seconds and for 2017 it ran in .43 seconds with conditional formatting to showcase the loses and gains these stocks were experiencing.
In order for the refractured code to be efficient, I created new loops with nested loops incorporated to find the tickerstartingPrice, tickerendingPrice, and tickervolumes to created arrays with the tickerIndex(i) identified. 

The results from the analysis showed that ENPH and Run both showcased a positive return for both years with ENPH showing the greatest positive return. TERP showed a lose in value both years, showing Steve that he should hold off on an investment with TERP. 6 stocks saw an increase in volume, one of which was DQ, which Steve’s parents had though was a good investment to consider. Overall, this analysis is able to show Steve which stocks have shown positive returns the 2 years it ran it’s data from and in the future he would be able to reference back to this macro year after year once he includes yearly data. 

Refactored Code:
 ![image](https://user-images.githubusercontent.com/102635884/164955743-4d3585b4-be14-40a8-9912-ea59c72322c2.png)
![image](https://user-images.githubusercontent.com/102635884/164955747-07a5f2fe-60bc-400d-960c-30b2dae8544d.png)
Refactored Code 2018
 ![image](https://user-images.githubusercontent.com/102635884/164955757-4dd990ec-6ba5-41a2-a71f-412e6d65c10b.png)
Refactored Code 2017
![image](https://user-images.githubusercontent.com/102635884/164955762-cec3e195-a094-4c11-96a1-6d73b3e9305a.png)

  
Original Code: 
 ![image](https://user-images.githubusercontent.com/102635884/164955737-062a9c19-5f28-4b66-b706-4725c1d6da89.png)
![image](https://user-images.githubusercontent.com/102635884/164955740-46de8c5f-4029-465e-b697-331fdd2a49a0.png)

 
Original Code 2018
![image](https://user-images.githubusercontent.com/102635884/164955727-1bbc1204-3981-4cb0-a963-670364b963b4.png) 
Original Code 2017
 ![image](https://user-images.githubusercontent.com/102635884/164955730-a32cff6f-61f6-4a93-8e1a-2aa926f99645.png)


Summary

Advantages of a refactored code

The advantage of a refactored code is that you are able to make your initial code more efficient. With my code I was able to reduce executing time by 81% for 2018 and 77% for 2017. This showed a huge reduction time in Steve’s ability to execute the analysis of thousands of rows in his dataset. 

Disadvantages of a refactored code

The disadvantage of a refactoring code is that you may lose your working macro when you start to create new lines to increase efficiency. In order to ensure if you did not lose the data it is recommended to use websites like Github to be able to reference back to your code in case it is lost in the process. It is always good to have  your original code stored so that you can also cross reference that you have all necessary information inputted when deleting lines of code. There are times that I lost lines of code when changing information in my loops, but I was able to find my original codes and restore what I had lost. 
