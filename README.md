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
### Confusion matrix:


<img width="299" height="673" alt="image" src="https://github.com/user-attachments/assets/b05b151f-b1d8-4891-8677-1a77b98a0157" />
<img width="282" height="657" alt="image" src="https://github.com/user-attachments/assets/06a8cabc-5466-4669-a3a5-1b7e63f17aaf" />
<img width="110" height="652" alt="image" src="https://github.com/user-attachments/assets/fcb49920-a30a-4d9d-b021-9322a08dbddf" />



### Accuracy per class: 

<img width="302" height="689" alt="image" src="https://github.com/user-attachments/assets/403a4d4a-077e-4753-9483-51f0ad559fbf" />



### Overall accuracy: 68.2%


## E. Model Testing
1.Juneberry

<img width="275" height="255" alt="image" src="https://github.com/user-attachments/assets/b9f17c6e-35dd-4cdb-87bd-6af77ada41b7" />
<img width="225" height="802" alt="image" src="https://github.com/user-attachments/assets/c5add5db-3525-48a0-baab-7bd08107cb47" />

2.Weeping willow

<img width="278" height="259" alt="image" src="https://github.com/user-attachments/assets/359c85ec-0ffd-4088-a7b3-36e03ac18963" />
<img width="229" height="841" alt="image" src="https://github.com/user-attachments/assets/3646e868-40e9-412a-8153-5dc8dfbe08ce" />


3.Olive tree

<img width="290" height="280" alt="image" src="https://github.com/user-attachments/assets/b777a32d-cd2f-4da8-9de1-3eb8e2b94fae" />
<img width="323" height="811" alt="image" src="https://github.com/user-attachments/assets/2719351e-b6d1-4dac-970e-9f7ca4cba883" />


4.Mediterranean cypress

<img width="244" height="238" alt="image" src="https://github.com/user-attachments/assets/10fc0b83-a836-4929-8bc6-0392f8cc0761" />
<img width="261" height="834" alt="image" src="https://github.com/user-attachments/assets/20f5a5d1-c15b-4b62-b9d2-18f7a33ca353" />


5.Sweetgum

<img width="260" height="283" alt="image" src="https://github.com/user-attachments/assets/687c96b4-1cf8-4814-8fc3-b6bfa445f1af" />
<img width="233" height="398" alt="image" src="https://github.com/user-attachments/assets/32e88b6a-1872-43a3-a628-3e67b6d22420" />


6.Ginkgo
   
<img width="246" height="256" alt="image" src="https://github.com/user-attachments/assets/a2cb8759-65bd-4d71-88d9-ababba3f6c46" />
<img width="233" height="677" alt="image" src="https://github.com/user-attachments/assets/1b75b0cd-aee1-4977-a428-a9fe2338e80b" />


7.Crape myrtle

<img width="272" height="268" alt="image" src="https://github.com/user-attachments/assets/9ea8d0ba-b0e3-4667-9f61-0d9a37407f31" />
<img width="296" height="652" alt="image" src="https://github.com/user-attachments/assets/551b7bcf-bbc5-4420-9f0c-4867b4ceea98" />


8.Flowering dogwood

<img width="251" height="251" alt="image" src="https://github.com/user-attachments/assets/4f721d1b-e5f7-4fcf-9a86-62355199b31d" />
<img width="220" height="628" alt="image" src="https://github.com/user-attachments/assets/8b23586b-dc0e-431b-96d3-e724fd61592a" />


9.Pink trumpet tree

<img width="246" height="247" alt="image" src="https://github.com/user-attachments/assets/5c554875-eda4-4fa7-9b21-e774932261a1" />
<img width="244" height="685" alt="image" src="https://github.com/user-attachments/assets/146270c6-be6f-46f9-bf31-e0e64ebcd0bf" />



10.Tropical almond 

<img width="269" height="268" alt="image" src="https://github.com/user-attachments/assets/d74a9142-5c93-4c6a-9f0e-2c7bbf802c38" />
<img width="264" height="596" alt="image" src="https://github.com/user-attachments/assets/3b176bca-95eb-4b34-be99-59ffd5fd0512" />






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

