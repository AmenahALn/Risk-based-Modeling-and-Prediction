## Risk-based Modeling and Prediction
we focused on predicting the occurrence and impact of the second wave of the epidemic. Our analysis involved the application of the return level approach, which required selecting an optimal threshold for identifying extreme events and estimating accurate return level values, MATLAB and R were utilized extensively for performing all the data analysis and computations in this project. Here is a summary of our findings:
#### 1. Optimal Threshold Selection
* Choosing a plausible threshold value is crucial, as it affects the precision and bias of the return level estimate.
* Using different methods to determine the appropriate threshold value for our data.
* The following Figure displays the peak values selected for infections.
<img src="https://github.com/AmenahALn/Risk-based-Modeling-and-Prediction/blob/main/mean_ira%20(2).jpeg" alt="Image" width="300" height="200">

#### 2. Return Level Estimation
* The projections for 2021 indicate that daily infections may exceed 4434, 4468, and 4498, with corresponding confidence intervals.
* The following Figure illustrates the return level estimates for the selected threshold values.
<div style="display: flex;">
  <img src="https://github.com/AmenahALn/Risk-based-Modeling-and-Prediction/blob/main/return.JPG" alt="First Image" style="width: 40%;">
  <img src="https://github.com/AmenahALn/Risk-based-Modeling-and-Prediction/blob/main/return_2.JPG" alt="Second Image" style="width: 40%;">
</div>
#### 3. Prediction of the Spread
* We employed the Gaussian2 model to estimate the value and timing of the expected peak for two different scenarios.
* The following Figure depicts the daily cases with three expected maximum peak values and their corresponding timing.
