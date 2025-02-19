# Assignment-4
#### The purpose of this code is to classify the echos in sea ice and lead and produce an average echo shape as well as standard deviation for 2 classes.

### Steps to follow
1. Download the Sentinel 2 image, which was previously saved.
2. Use the K mean method to plot the image to classify sea ice and lead. Include the colour bar to show the cluster label of the image which ranges from -1 to 1.
3. Now import the same image and use GMM(Gaussian Mixture Method) to plot the image this time. Use same scale for colour bar so that it is easy to compare.
4. Import Sentinel 3 data from the previously saved image. It is essential to do some preprocessing of data such as calculating variables such as peakiness and SSD(Stacked Standard Deviation) and deleting all NAN data.
5. Plot the mean and standard deviation of sea ice and lead. 
