# SkySegmentationPython
Sky Segmentation Algorithm - Python script

This python script help to obtained a sky mask from a raw image using computer vision technique. White area in the obtained sky mask represent sky region while black area in the obtained sky mask represent non-sky region.

# Dataset Used to evaluate the performance of the sky segmentation python script
We selected image dataset captured by camera 4232, 9483 and 10917 in the SkyFinder database to evaluate the performance of our algorithm. SkyFinder dataset consist of image
dataset captured by 53 different camera with approximately 90,000 images in the dataset.



# How to run skyPixelSegmentation.py

The script could be run in two way which is using spyder IDE or command prompt. Using Spyder IDE is more suitable when you wish to examine the output of each step while using
command prompt are more suitable to process a folder. 

Using Spyder IDE
```
Step 1: Make sure that all library is installed.
Step 2: Open Spyder IDE, set the variable ‘DEBUG_MODE’ to true.
Step 3: set the IMAGE_PATH variable to the raw image that you wanted to process.
Step 4: Run the script, you should be able to see the output of each step in a pyplot figure. The output of final sky mask will be in current directory.
```
Using Command prompt
```
Step 1: Make sure that all library is installed.
Step 2: Navigate to script directory in command prompt using 'cd' command.
Step 3: Execute the script using the following command ‘python skyPixelSegmentation.py –image_path YOUR_RAW_IMAGE_PATH’.

NOTE: please make sure the DEBUG_MODE is set to false.
Step 4: You should be able to obtain the output sky mask.
```
