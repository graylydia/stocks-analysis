# Analyzing the Green Energy Stock Market

## Overview of the Project

### Purpose
Steve’s parents are looking to invest in green energy so we helped Steve create a Visual Basic for Applications code that analyzed a dozen of green energy stocks. Taking it another step, we refactored the original code to allow it to run more quickly and smoothly. In addition to quicker run time, refactoring the code allowed it to run for the entire stock market which included thousands of different data points. Steve and his parents can now look through the entire stock market for green energy with visual indicators and better readability. 

### Analysis

<img width="515" alt="Original_AllStocksAnalysis" src="https://user-images.githubusercontent.com/103657822/167312150-5a23cfeb-fde4-4856-994e-9750de617159.png">

The picture above shows the original code that we used. As you can see, we used nested For loops to run through the data for each ticker and as a result the run time was longer. In the outer For loop we are initializing the correct ticker and declaring that totalVolume's value is 0. We declare that totalVolume's value is 0 so that we get the correct output and have a value to add to. In the inner For loop we are now going through the data. By applying If-Then statements we are adding the volume for the current ticker to the last totalVolume value. Then we are giving startingPrice and endingPrice their value which we use later to calculate the return on the stock. This process occurs for each ticker and is outputted. 

<img width="678" alt="Refractored All Stocks Analysis" src="https://user-images.githubusercontent.com/103657822/167313226-3354d25f-59ab-4f09-80ea-68606f1d6ad7.png">
<img width="244" alt="Refractored_AllStocksAnalysis2" src="https://user-images.githubusercontent.com/103657822/167313289-1019e0b7-1dff-460d-a923-1cd75d2dca3e.png">

The code above is our refractored All Stocks Analysis. In the refractored code we used separate For loops. The first For loop set tickerVolumes value to 0. Then the code would move onto the next For loop which gave each array their volume, starting price, and ending price.

### Results

<img width="259" alt="Original_AllStocksAnalysis_2017" src="https://user-images.githubusercontent.com/103657822/167314002-0aaddb54-7c14-43b6-af51-ad27ace8abb4.png">      <img width="269" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/103657822/167314144-45db28bc-74e4-4a70-ae92-7720aa56677f.png">
The image on the left shows that it took 0.7460938 seconds for the original code to run. Whereas the image on the right shows that it took 0.14484375 for the refractored code to run. The time difference between the two is 0.5976563. That is 19.90% faster than the original code.


<img width="260" alt="Original_AllStocksAnalysis_2018" src="https://user-images.githubusercontent.com/103657822/167314405-9481ac90-4824-4850-adee-6b609bde79ae.png">      <img width="267" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/103657822/167314413-9ab18df0-da97-44f7-83f6-1cc22c10fd59.png">


