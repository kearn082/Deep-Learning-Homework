# **Deep Learning - Unit 14 Homework**
## **Objective:**
The objective of this homework assignment was to determine if the Crypto Fear and Greed Index (FNG) or the simple closing price data would be a better predictor for Bitcoin price. To do this we were tasked with building and evaluating deep learning models and reading in the price data and the FNG data to compare the two models. 
## **Findings:**
### *Which model had the lowest loss?*
Using a window size of 3, 30 epochs and a batch size of 3 training both models, using the closing price yielded a lower loss (0.0095) than the FNG (0.1043).
### *Which model tracks the actual values best over time?*
The closing price model tracks the actual values much more closely over time. The FNG model shows nearly no fit to the actual data. 
### *Determine the appropriate Window Size for the model.*
I determined that 3 was the appropriate Window Size for the model. As I decreased from 3, the plow of the model began to look like it was overfit. As I increased from 3 then the loss began to rise and the fit became worse. 