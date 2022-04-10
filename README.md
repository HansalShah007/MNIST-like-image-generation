# MNIST like image generation

## How to use?
  - Download the zip folder of this repository and open the notebook using Jupyter.
  - Make sure your local system has all the required libraries before you run the code for importing all of them.
  - Run the code under the title `Code for capturing and generating images`. Allow the notebook to access your webcam. A green box will appear which indicates the area that will be captured and processed. Hence, make sure that your object lies in this region of interest (ROI).
  - Press `C` on your keyboard to capture an image.
  - To quit, press `Q`. 
  - Once you quit, the images will be saved in a new folder created with the name `Captured Grayscale Images`.
  - Run all the remaining cells to generate a csv file for the images and visulaize the data by specifying a valid path to `generated_data.csv` file which will be generated once you run the code cell under the title `Generating a CSV file`.

## Specifications of generated images
  - Type: Grayscale
  - Height: 28 pixels
  - Width: 28 pixels

## About generated_data.csv
  - Every row of the csv file corresponds to a single image data. It consists of 784 gray-scale pixel values and 1 label. You can set the label by manipulating the code under the title of `Extracting the pixel values of all the grayscale images`. Here, you need to mention the label in this line of code:
```
temp.append('Label value')
```
