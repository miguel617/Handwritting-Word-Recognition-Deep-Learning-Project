# Handwritting-Word-Recognition-Deep-Learning-Project
 From image to text - a handwriting recognition tool prototype using Image Classification - Deep Learning in DataBricks.


In this project, we build an image processing tool, which is usually a task for big data platforms. Hence, that's what we propose to do with this "prototype":

1) Start with three type of images (landscapes, pictures of the Simpsons, and handwriten words);
2) Compare these with a pre-trained image recognition model, following an example from the databricks documentation;
3) Apply a logistic regression to these images to separate them in their 3 categories: landscapes, simpsons and words;
4) Apply a convolutional recursive neural network to our word images, to convert the picture to text;
5) Use an oxford Dictionary API to extract a definition for any word. This is done so we have a string of text with the meaning for each word we're analysing, because of the next step, which is to group related documents together;
6) To automattically group documents together by content (say, we would like to gather notes and documents from the Analysing Big Data course in one folder and the Machine Learning course in another folder) - we will use K-Means to do word clustering;
7) Simulate a streaming process that detects new images from a landing folder, and test our own images with the trained models.

**The project was done in DataBricks framework and the HTML notebook can be found at "Handwritten Word Recognition Project.html" and a visual presentation of the results can be seen at "Handwritten Word Recognition Project.pdf".**
