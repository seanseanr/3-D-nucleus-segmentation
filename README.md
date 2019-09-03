# 3-D-nucleus-segmentation
3-D nucleus segmentation. In theses project I got problem about the number of training data,
which is too small. And the model to train and do the segmentation. I latter choose mask-rcnn
model which is a newest one of segmentation at that time. About the problem of small number
of training data I use the ndimage function to get single mask image of every nuclei in a
training image which contains many many masked nucleus.
