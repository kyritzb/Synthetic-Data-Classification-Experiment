# Improving CNN Performance through Generative AI: A Data Augmentation Approach

This project investigates the impact of generative AI on the performance of convolutional neural networks (CNNs) in image classification tasks, specifically in the context of limited data. Three distinct CNN models were implemented and com- pared, each trained on a unique dataset: the original images of cats and dogs, the same images augmented by OpenAI’s DALL-E, and a further enhanced dataset with neural style transfer applied. The findings highlight the potential of using generative AI for data augmentation. The model trained on the most augmented dataset achieved the highest accuracy of 90.86% on the test set, which was a 3.16% increase over the model trained on the original dataset. The study underscores the value of integrating state-of-the-art AI methods to improve the generalizability and performance of CNNs, even in data-limited scenarios.

## Downloads

1. Paper: https://drive.google.com/file/d/1h4bzdXrKR5lW5oJM01WHtaV-kIxDoypu/view?usp=share_link
2. Data: https://drive.google.com/drive/folders/1OiczOR1XL3g0A0TXQryzC6PhrivzBytS?usp=share_link


**The data should be at the root of the project directory in the folder named "data".**

The repository contains three main Jupyter Note- book files: data.ipynb, styletransfer.ipynb, and main.ipynb, each serving a specific purpose in the experimentation process.

### data.ipynb
This notebook file allows the generation of variations of the original images using OpenAI’s DALL-E model. By executing the code in this notebook, you will be able to augment the dataset with synthetic images that mimic the creativity of human artists. These generated images serve as an additional source of training data for the subsequent convolutional neural network models.

### styletransfer.ipynb
In this notebook, the images from the original dataset, as well as the DALL-E augmented dataset, can be transformed into new styles using neural style transfer techniques. By running the code provided in this notebook, you can convert the images into diverse artistic styles, further enriching the dataset’s complexity and variability. The result- ing style-transferred images are instrumental in training the third convolutional neural network.

### main.ipynb
The primary notebook file, main.ipynb, focuses on the training and evaluation of the convolutional neural network models. By executing the code in this notebook, you can run the CNN training process using the augmented datasets created through DALL-E and style transfer techniques. The notebook allows for a comprehensive comparison of the performance of the three CNN models trained on different datasets, highlighting the impact of generative AI on image classification tasks.
