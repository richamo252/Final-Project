# Cancer Cell Detection

Description: 
This project proposes a specialized AI model which is designed to classify cell images into three categories: "malignant", "benign", and "normal". By training on a diverse dataset of cell images, the AI will learn how to accurately identify and categorize cell types based on visual analysis, and the cell size. Users will interact with the system by inputting cell images for classification, receiving instantaneous feedback on cell condition. This application holds promise in medical diagnostics. helping radiologists job, making it easier for them to understand when looking at a cell that is malignant, benign or normal, supporting healthcare professionals in early detection and treatment of cancerous cells.


![add image descrition here](direct image link here)

# The Algorithm

Description: 
It would include a diverse dataset of cell images labeled as "malignant", "benign", and "normal". This dataset is crucial for training the AI model to recognize and classify different cell types accurately. The main part of this project is the AI model. It is based on convolutional neural networks (CNNs), which are highly effective in any image classification tasks. I used ImageNet because b0y training my model with the ImageNet, users can improve the accuracy of the AI system. My dataset’s ensures that model can learn to generalize well across different types of images and in different categories. I have used this ImageNet to my dataset for cancer to re-train my AI to get image results back when a user wants to see a malignant, benign or normal cell. Since my project is based on a image calssification and CNNs, the AI would be able to automatically learn features from the images that I imported from a worldwide dataset site. The image would show, textures, patterns and size, which are essential for distinguishing between different cell types. This involves preprocessing the images (resizing and normalization) and then passing them through the trained CNN to generate predictions (malignant, benign, or normal). The AI model will utilize techniques from computer vision to analyze cell images. I am using a Jetson nano, which is a Nvidia Jetson and a series of embedded computing boards from Nvidia. I also used an ImageNet, which is a large-scale dataset of annotated images organized into hierarchical categories. The ImageNet serves as a benchmark for training and testing AI models in image classification. So the model that I trained on the ImageNet is learning how to distinguish between a 3 numbers of object categories, which is analogous to the task of distinguishing between different cell types (malignant, benign, normal) in my projet.


## Running this project
1. Download this dataset, https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset. 
2. Then when you have dowloaded it, transfer this into the VS code file.
4. Then after you do that, split the folders into sections so that it won't have to download the large data.
5. Then you would have to add the code I have for the "Train Classification".
6. When you have finished that, there will be some debugs, just make sure you know what your foldres look like and make sure you label them the write way, sometimes you will haev to rename based on issues you face. For example, i had to rename my file, because 1, it was to long, and 2, it did not have _ after every word (Cancer_Data_file).
7. Then after you are done with that, you should see, that you have a larger dataset file, and within that you should have 3 classes within it. But depending on what you are doing, like for example, if you are doing something like a dog and cat image calssification, you would have one large file, and then you would have 2 classes within that.
8. After that, you might run into some debugging. For example, if it says something like "No File or directory", then you would have to make sure you know what and where your files are located and the right name you have labled it as. When you have figured that out, then you might have to comment some stuff out. Another example, I had run into this problem as well. When you had a ! in you code, and it showed a red line, then that is your cue to add a comment. The way you add a comment, you would have to add # before the line, delete the !. Another problem that you might have to run into would be something like "No module named 'onnxruntime", you will have to take that out if you are working with VS code, but if you are working in collab, then you can keep it. I only ran into that problem because i was working within the VS code terminal, and not the collab.
9. After you finish all your debuging, then you should be home free. Your code should be good and your AI should be able to run and re-train the AI. 
10. Just press the run botton, and when you have run the code, you will be able to see the traning start.
11. When there are many lines coming down in the terminal, then you know that it's working, and the AI is traning the model to give you an image
12. When you finish, it should give you a result, and when it does, on the top left conner of the image, you should see a score. That is what we call a confident score.
13. If this test had worked, you confident score should have come to about 33-34% right. It is only this low because i have 3 classes running. So it's bacically saying 2 classes would give you 50-50% , just like that, since this one has 3 classes, it would show you 33-34%
14. If the test did not work, either because the code was stuck, or the image gave you the wrong image and the score came to be 5-6%. 

[View a video explanation here](video link)
