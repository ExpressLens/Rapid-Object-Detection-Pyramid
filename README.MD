
# Rapid Object Detection using Feature Pyramid

This repository houses ExpressLens's implementation of the object detection method referenced in the paper available [here](http://vision.cornell.edu/se3/wp-content/uploads/2014/09/DollarPAMI14pyramids_0.pdf).

## Implementation Details
The implementation has been carried out using C++. The used structures include Random Forest and Boosted Decision Trees. The performance has been measured and found to be on par with the results mentioned in the paper (Random Forest: 14fps, Boosted Trees: 18fps). Additionally, ACF feature has been used.

## Results
The detection system has been tested on pedestrians and the results are promising. The ground truth is illustrated in green and the detected pedestrians in blue.

![acf](https://cloud.githubusercontent.com/assets/13601723/15353065/21459712-1d22-11e6-89b0-e46d5676dafe.png)