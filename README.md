# Animal-Classifier-AI
A deep learning model using Transfer Learning (MobileNetV2) to classify five animal species: Cats, Dogs, Cows, Lions, and Deers.
Multi-Species Animal Classifier (99.5% Accuracy)
This project is a Deep Learning application built with TensorFlow and Keras. It identifies five different species of animals with high precision using a pre-trained neural network.

---Project Overview
The model was trained to distinguish between domestic and wild animals.

Domestic Animals: Cat, Dog, Cow

Wild Animals: Lion, Deer

Final Performance: The model achieved a Training Accuracy of 99.57% and a Validation Accuracy of 98.80%.

  Technical Implementation
Transfer Learning: Used the MobileNetV2 architecture to leverage pre-trained weights from the ImageNet dataset.

Data Augmentation: Implemented image rotation, flipping, and zooming to prevent Overfitting and help the model learn from 70 images per class.

Optimization: Used the Adam optimizer and Categorical Crossentropy loss function.

--- Dataset Structure
The data is organized into three standard subsets:

Train: Used to teach the model animal features.

Validation: Used to tune the model during training.

Test: Used to verify real-world performance on new images.

---How to Run
Click the "Open in Colab" button at the top of the notebook.

Upload the Animal_Data.zip file to the Colab environment.

Run the cells to see the training logs and testing results.

Use the provided "Test" cell to upload your own photo and see the AI's prediction!
