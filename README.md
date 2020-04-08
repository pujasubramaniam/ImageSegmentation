# ImageSegmentation
Image Segmentation Project completed in R

The utilization of image segmentation can be seen in a variety of industries – medical diagnosis, autonomous driving, and face recognition. 
Image pixels can be interpreted as nodes of a graph with edges connecting neighboring pixels; this approach to viewing images allows us to use different network optimization methods to conduct image analysis. In this project, I utilize the max-flow/min-cut approach to do image segmentation to segment an image into the foreground and background. This can be completed several ways; I include 2 in my project. The first is naïve thresholding, where the parameter choices are set somewhat arbitrarily. The other is using the min-cut/max-flow approach, where we compute matrices to differentiate between foreground and background pixels, as well as the weights on the edges of connecting node pairs. 

