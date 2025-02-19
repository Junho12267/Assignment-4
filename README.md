# Assignment 4
### The purpose of this assignment is to classify the echos in sea ice and lead and produce an average echo shape and standard deviation for 2 classes. This can then be compared with the data from the European Space Agency.

#### Steps to follow. (This summarises the key steps taken to calculate the eco shape, mean and standard deviation. For more detailed code refer to the Chapeter1_Unsupervised_Learning_Method.jpynb)
1. Download the Sentinel 2 image, which was previously saved.
2. Use the K mean method to plot the image to classify sea ice and lead. Include the colour bar to show the cluster label of the image which ranges from -1 to 1.
   
   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20212204.jpg)
   
   Figure 1
   
3. Now import the same image and use GMM(Gaussian Mixture Method) to plot the image this time. Use the same scale for the colour bar so that it is easy to compare.
   
   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20212848.jpg)
   
   Figure 2
   
4. Import Sentinel 3 data from the previously saved image. It is essential to do some preprocessing of data such as calculating variables such as peakiness and SSD(Stacked Standard Deviation) and deleting all NAN data.
5. Plot the mean and standard deviation of sea ice and lead with echo number on the x-axis and deviation from the mean on the y-axis. Make sure to include the axis label and title.
   
    ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20213324.jpg)
   
   Figure 3
   
6. Plot the echos in a histogram including the total echos, lead clusters and sea ice clusters. Make sure to include the axis label and title.
   
   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20214104.jpg)
   
   Figure 4
   
   
7. Create a scatter plot of sea ice and lead for clustered data.
   
   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20214104.jpg)
   
   Figure 5
   
8. Align the waveform and compare the output with ESA(European Space Agency) data using a confusion matrix.
   
   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20220204.jpg)
   
Figure 6

   ![Image Description](https://github.com/Junho12267/Assignment-4/blob/main/Screenshot%202025-02-19%20220234.jpg)
   
Figure 7


   #### Conclusion: The Sentinel-2 and Sentinel-3 data acquired are very accurate as the accuracy of the confusion matrix is around 99 to 100% based on confusion matrix. However, the echos tend to have quite a high standard deviation based on Figure 3 especially when the eco number is between 100 to 120. This can be because there are more data in those regions which led to higher standard deviation. However, the quality of data is very high in general. 
   
