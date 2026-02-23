# -Plant-Species-Image-Classification-

## A. Project Overview
This project focuses on developing a deep learning model to classify different plant species based on image data. The model was trained using 50 epochs, a batch size of 16, and a learning rate of 0.001 to achieve stable and efficient learning. Performance was evaluated using accuracy per plant species, allowing detailed analysis of how well the model recognizes each type of plant. The results show varying accuracy levels across 20 plant species, highlighting both strong classifications and areas that need improvement.

<img width="999" height="667" alt="image" src="https://github.com/user-attachments/assets/5b3bca85-b7b0-4819-b813-543e868cc482" />

## B. Plant Species Section
Common Name:Juneberry 
Scientific Name: Amelanchier

Juneberry (Amelanchier) is a small deciduous shrub or tree known for its sweet, edible berries that ripen in early summer. The berries are often dark purple and resemble blueberries, making them popular for jams, pies, and fresh eating. Juneberries also have attractive white flowers in spring and vibrant fall foliage, making them both a food source and an ornamental plant.

## C. Model Training Details
Epochs: 50
Batch size: 16
Learning rate: 0.001
Number of image per class: 250

## D. Model Evaluation
###Confusion matrix:


<img width="299" height="673" alt="image" src="https://github.com/user-attachments/assets/b05b151f-b1d8-4891-8677-1a77b98a0157" />
<img width="282" height="657" alt="image" src="https://github.com/user-attachments/assets/06a8cabc-5466-4669-a3a5-1b7e63f17aaf" />
<img width="110" height="652" alt="image" src="https://github.com/user-attachments/assets/fcb49920-a30a-4d9d-b021-9322a08dbddf" />



###Accuracy per class: 

<img width="302" height="689" alt="image" src="https://github.com/user-attachments/assets/403a4d4a-077e-4753-9483-51f0ad559fbf" />



###Overall accuracy: 68.2%


## E. Model Testing






## Reflection Questions
1. How did the number of images per class affect your model’s accuracy?
   
answer: Classes with more images generally had higher accuracy, but not always.
For example:
Norfolk Island Pine (45 samples) → 1.00 accuracy
Acacia saligna (49 samples) → 0.88
Magnolia grandiflora (51 samples) → 0.84

2. Which plant species were most commonly misclassified and why?

answer: The most commonly misclassified species were Sweetgum, Olive tree, Silk Oak, Juneberry, and Ginkgo, likely because their leaves share similar shapes, textures, and colors, and because of variations in lighting and background conditions.

3. How did changing the epochs, batch size, or learning rate affect the training results?

answer:Increasing the number of epochs improved accuracy up to a certain point, but too many epochs may have caused overfitting, while learning rate and batch size influenced stability, with lower learning rates generally producing more stable and better final results.

4. What challenges did you encounter during dataset collection and labeling

answer: The main challenges during dataset collection and labeling included class imbalance, visually similar species, inconsistent image conditions, and the possibility of incorrect labeling.

5. If you were to improve your model, what specific changes would you make and why?

answer: To improve the model, I would collect more images for low-performing classes, apply data augmentation, use a pretrained CNN model through transfer learning, and fine-tune hyperparameters such as learning rate and regularization to improve generalization and reduce misclassification.

