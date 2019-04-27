# DIP-Kriging
An image downscaling algorhitm for the final project. [Deep Image Prior](https://dmitryulyanov.github.io/deep_image_prior) and Kriging Regression are used to downscale fine images. 


## Deep Image Prior (DIP)
- For introduction about Deep Image Prior, you can see [the original paper](https://dmitryulyanov.github.io/deep_image_prior).

- The codes used in this project is [a simplified version implemented using tensorflow](https://github.com/beala/deep-image-prior-tensorflow).


## Ordinary Kriging 
- The Ordinary Kriging is to remove the trend (DIP generated image) from the reference iamge, and then predict the residuals using the distance-based covariance. 

## Workflow


![alt text](https://github.com/JWang233/dip-kriging/blob/master/workflow.png)
