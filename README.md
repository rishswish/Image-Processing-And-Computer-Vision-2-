# Image-Processing-And-Computer-Vision-2

Lab1
This dataset contains Malaria cell images classified into “Paratisized” and “Uninfected.”
The steps involved in the experiment are as follows:
a. Preparing the dataset: Download and preprocess the dataset. Resize the images and perform one-hot encoding.
b. Designing the model: Design the CNN model.
c. Training the model: Initialize the Custom CNN and transfer learning models (with pre-trained weights if available) and fine-tune them using the training dataset. Define the loss function and optimization algorithm. Monitor the training process and adjust 3-4 hyperparameters.
d. Post-processing and evaluation: After training, apply the trained model to test images. Calculate evaluation metrics such as to assess the model's performance

Lab2
Use the given dataset and perform the YOLO task.
The steps involved in the experiment are as follows:
1. Load and preprocess the video footage.
2. Download and set up the pre-trained YOLO model.
3. Perform object detection on each frame of the video.
4. Visualize the results and analyze the performance.
5. Bonus Task: Perform Real-Time object-detection using the webcam. This can be any object-detection task and not particularly identification of vehicles

Lab3
Dataset: Use sample images containing text.
The steps involved in the experiment are as follows:
1. Import Tesseract OCR and relevant libraries.
2. Apply Tesseract on the sample images.

Lab4
Use the given dataset and perform the following tasks:
This dataset contains a zip file of RGB images to train the GAN.
The steps involved in the experiment are as follows:
a. Preparing the dataset: Download and preprocess the dataset. Download the zip file on colab (using “ !unzip <file path>” command).
b. Parse only a part of the dataset to save computation and convert each image to a grayscale image.
c. The Generator: Prepare a Generator model that would take in a grayscale image (x) and produce a RGB image(G(x)). Note, x will be a tensor of shape ( batch size , 120 , 120 , 1 ) and the output G(x) will have a shape ( batch size , 120 , 120 , 3 )
d. The Discriminator: Prepare a Discriminator model, represented as D , that will take in the real image y ( from the training data ) and the generated image G(x) ( from the generator ) to output two probabilities.
e. Loss Functions: Define Loss Functions for the Generator and Discriminator.
f. Training: Train the GAN on the giving dataset.
g. Results: Display the Grayscale input, Colourized output and the Groundtruth side-by-side.

Lab5
Analyse body postures/ keypoints using MoveNet






