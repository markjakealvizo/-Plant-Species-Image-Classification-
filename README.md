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
Juneberry:

<img width="256" height="254" alt="image" src="https://github.com/user-attachments/assets/5e220400-f795-4e62-9ef4-508f20b74aea" />
<img width="234" height="780" alt="image" src="https://github.com/user-attachments/assets/d8fe31b0-184a-4157-a6d7-8ded94dba31d" />

Weeping Willow: 

<img width="312" height="281" alt="image" src="https://github.com/user-attachments/assets/b309aa64-49cc-4023-a2b9-ca2f312e15df" />
<img width="234" height="783" alt="image" src="https://github.com/user-attachments/assets/9bc3fe00-fe1d-4f77-a452-4ff5c38bf899" />

Olive Tree: 

<img width="289" height="294" alt="image" src="https://github.com/user-attachments/assets/c5bba173-291e-4491-873b-c319fdc3a19c" />
<img width="217" height="729" alt="image" src="https://github.com/user-attachments/assets/2d8afccd-d2a3-4597-80c3-89dd121def99" />

Mediterranean cypress:

<img width="241" height="235" alt="image" src="https://github.com/user-attachments/assets/9e9a8088-bfc4-42da-b0d6-b5f75ccf6e93" />
<img width="239" height="781" alt="image" src="https://github.com/user-attachments/assets/92a816b9-d31d-4abf-b3ba-5e797dc2a0cb" />

Sweetgum:

<img width="272" height="262" alt="image" src="https://github.com/user-attachments/assets/027971e2-22b9-43be-9df6-2f604ef088c5" />
<img width="234" height="783" alt="image" src="https://github.com/user-attachments/assets/293dcdfc-1f78-465a-a824-841c787baa60" />


Gingko:

<img width="302" height="293" alt="image" src="https://github.com/user-attachments/assets/f32a4ad0-76d1-48a9-92e2-aa3f4bab3ee6" />
<img width="234" height="779" alt="image" src="https://github.com/user-attachments/assets/46247927-8ebc-4e14-bde9-f035b53b06d1" />


Crape myrtle:

<img width="311" height="299" alt="image" src="https://github.com/user-attachments/assets/eecad668-78da-468c-bff2-4d58ff1ef58c" />
<img width="239" height="784" alt="image" src="https://github.com/user-attachments/assets/ab3529f6-30d8-41d7-8efd-6ac3bd620d9e" />


Flowering dogwood:

<img width="340" height="329" alt="image" src="https://github.com/user-attachments/assets/a23095a0-7e46-4509-a572-bcf8dde9c5ab" />
<img width="234" height="780" alt="image" src="https://github.com/user-attachments/assets/2ea653fa-f0b6-4596-a6fe-78fe95f9b5f1" />


Pink trumpet tree:

<img width="311" height="303" alt="image" src="https://github.com/user-attachments/assets/6ad1eca5-ebff-4d8b-8c74-a4da402fcd07" />
<img width="267" height="832" alt="image" src="https://github.com/user-attachments/assets/6925e462-b9f8-4772-8225-1490a485a49b" />


Silk tree:

<img width="321" height="312" alt="image" src="https://github.com/user-attachments/assets/889ac835-a92a-47ac-8503-5d3f019d9205" />
<img width="242" height="786" alt="image" src="https://github.com/user-attachments/assets/3da1919f-4fc9-45e9-b7ef-7cd1d8c0eb1e" />












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

