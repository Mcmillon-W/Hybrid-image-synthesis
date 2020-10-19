# Hybrid-image syntesis
The Code is implmented in Google colab notebook proj1.ipynb. The function which correlates the kernel/filter with the image is coded in Python my_imfilter.py and needs to be uploaded into the google colab notebook first. 
The function can be tested using another google colab notebook proj1_test_filtering.ipynb and trying out other various filters.
Similarly the vis_hybrid_image.py needs to be uploaded for scaling the hybrid image. The Gaussian kernel is taken from fspecial('Gaussian', (cutoff_frequency*4)+1, cutoff_frequency) in matlab.
Where cutoff_frequency is 7.
The weights have been saved in gauss.xlsx which also have to uploaded with the proj1.ipynb for the values are extracted using pandas.
Upload the 2 images which you want to combine (in this case the dog.bmp and cat.bmp) and you will get your result.
Note: It will take a significant time to run as the gaussian kernel is very big and 29^2 operations are occuring in every pixel of the image.
