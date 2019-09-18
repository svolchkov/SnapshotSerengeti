1. The following packages and libraries have been used to create and run the Jupyter notebook:

- Anaconda 6.2.0 for Python 3.  This includes IPython and numpy 1.14.3

After installing Anaconda, it should be easy to run "conda install <package name> to install the following:

- OpenCV 3.4.1
- tensorflow 1.12.0
- keras 2.2.4

(Most likely, it will work with the latest versions of the above libraries.)

2. The archive will need to be unpacked to the root folder for IPython notebooks, such as C:\Users\<username> on a Windows machine. 
The contents of the archive include the notebook, the .h5 file with the model and the weights and an images subfolder which also contains
a data.csv file with the labels.

3. Open the notebook and select Cell -> Run All Cells from the menu at the top.

4. The output of the last cell should include several test images with predictions and ground truths.       