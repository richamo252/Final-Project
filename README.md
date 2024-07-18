# Cancer Cell Detection

Description: 
This project proposes a specialized AI model which is designed to classify cell images into three categories: "malignant", "benign", and "normal". By training on a diverse dataset of cell images, the AI will learn how to accurately identify and categorize cell types based on visual analysis, and the cell size. Users will interact with the system by inputting cell images for classification, receiving instantaneous feedback on cell condition. This application holds promise in medical diagnostics. helping radiologists job, making it easier for them to understand when looking at a cell that is malignant, benign or normal, supporting healthcare professionals in early detection and treatment of cancerous cells.


![add image descrition here](direct image link here)

# The Algorithm

Description: 
It would include a diverse dataset of cell images labeled as "malignant", "benign", and "normal". This dataset is crucial for training the AI model to recognize and classify different cell types accurately. The main part of this project is the AI model. It is based on convolutional neural networks (CNNs), which are highly effective in any image classification tasks. I used ImageNet because b0y training my model with the ImageNet, users can improve the accuracy of the AI system. My dataset’s ensures that model can learn to generalize well across different types of images and in different categories. I have used this ImageNet to my dataset for cancer to re-train my AI to get image results back when a user wants to see a malignant, benign or normal cell. Since my project is based on a image calssification and CNNs, the AI would be able to automatically learn features from the images that I imported from a worldwide dataset site. The image would show, textures, patterns and size, which are essential for distinguishing between different cell types. This involves preprocessing the images (resizing and normalization) and then passing them through the trained CNN to generate predictions (malignant, benign, or normal). The AI model will utilize techniques from computer vision to analyze cell images. I am using a Jetson nano, which is a Nvidia Jetson and a series of embedded computing boards from Nvidia. I also used an ImageNet, which is a large-scale dataset of annotated images organized into hierarchical categories. The ImageNet serves as a benchmark for training and testing AI models in image classification. So the model that I trained on the ImageNet is learning how to distinguish between a 3 numbers of object categories, which is analogous to the task of distinguishing between different cell types (malignant, benign, normal) in my projet.


## Running this project

1. Just press the run botton, and when you have run the code, you will be able to see the traning start. 
2. When there are many lines coming down in the terminal, then you know that it's working, and the AI is traning the model to give you an image
3. When you finish, it should give you a result, and when it does, on the top left conner of the image, you should see a score. That is what we call a confident score.
4. If this test had worked, you confident score should have come to about 33-34% right. It is only this low because i have 3 classes running. So it's bacically saying 2 classes would give you 50-50% , just like that, since this one has 3 classes, it would show you 33-34%
5. If the test did not work, either because the code was stuck, or the image gave you the wrong image and the score came to be 5-6%. 

[View a video explanation here](video link)
