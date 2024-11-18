# Meesho-AI-Data-Challenge-2024
Team Powerpuff Boys' Solution to the Visual Taxonomy Challenge

We have provided 4 ipynb files, each for fine-tuning a respective model on the dataset.
How to run:
1. Navigate to the dataset: https://www.kaggle.com/datasets/biswadeeppurkayastha/m1dataset
2. Create a new notebook.
3. Import the ipynb file for the model that you want to train
4. Add the accelerator that you want: T4, P100(recommended) or TPU
5. Run all cells.
6. After the execution, you will get the model in /kaggle/working of the format *.pth


## Limitation
Upon human evaluation of approx. 1000 images along with results from LLaMA 3.2 7B vision model, we concluded that the ground truth may have deviated from the actual truth provided in the image(for eg. in many cases of images with long sleeves, the ground truth provided had short sleeves in it and some images in which there were 4 men tshirts, the color attribute was misleading it had the value ‘default’ for some images and ‘multicolor’ for other images. These are few examples which we found out; There might be other such potential examples). 
