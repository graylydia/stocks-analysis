# Analyzing the Green Energy Stock Market

## Overview of the Project

### Purpose
Steve’s parents are looking to invest in green energy so we helped Steve create a Visual Basic for Applications code that analyzed a dozen of green energy stocks. Taking it another step, we refactored the original code to allow it to run more quickly and smoothly. In addition to quicker run time, refactoring the code allowed it to run for the entire stock market which included thousands of different data points. Steve and his parents can now look through the entire stock market for green energy with visual indicators and better readability. 

## Results

### Analysis

<img width="515" alt="Original_AllStocksAnalysis" src="https://user-images.githubusercontent.com/103657822/167312150-5a23cfeb-fde4-4856-994e-9750de617159.png">

The picture above shows the original code that we used. As you can see, we used nested For loops to run through the data for each ticker and as a result the run time was longer. In the outer For loop we are initializing the correct ticker and declaring that totalVolume's value is 0. We declare that totalVolume's value is 0 so that we get the correct output and have a value to add to. In the inner For loop we are now going through the data. By applying If-Then statements we are adding the volume for the current ticker to the last totalVolume value. Then we are giving startingPrice and endingPrice their value which we use later to calculate the return on the stock. This process occurs for each ticker and is outputted. 

<img width="678" alt="Refractored All Stocks Analysis" src="https://user-images.githubusercontent.com/103657822/167313226-3354d25f-59ab-4f09-80ea-68606f1d6ad7.png">
<img width="244" alt="Refractored_AllStocksAnalysis2" src="https://user-images.githubusercontent.com/103657822/167313289-1019e0b7-1dff-460d-a923-1cd75d2dca3e.png">

In the refractored code we used separate For loops. The first For loop set tickerVolumes value to 0. Then the code would move onto the next For loop which gave each array their volume, starting price, and ending price.
