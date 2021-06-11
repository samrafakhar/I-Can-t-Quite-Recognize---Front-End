# I-Can-t-Quite-Recognize---Front-End
A HTML, CSS and JavaScript website demonstrating the functionalities of the project.

We have created the frontend of the I Can't Quite Recognize - the project that explains how Facial Recognition systems are affected by Adversarial Attack. 
___
# Project Functionalities
The names of the files are quite explanatory. However start navigation from Mainpage.html 
`details.html` is help screen
## Introduction Screen
When a user uses our system, he is first presented with a screen which provides him with a brief introduction and explanation of what the system does.

![image](https://user-images.githubusercontent.com/68595241/121756046-503e5e00-cb32-11eb-8515-e0513962b0e5.png)

## Image Selection Screen
Next the user is presented with a screen with a collection of images. This selection screen provides the user with a number of images from which he can select any one he wants to perform an adversarial digital attack upon. User selects one of these images to proceed.

![image](https://user-images.githubusercontent.com/68595241/121756267-f38f7300-cb32-11eb-9189-77cca0a95a1e.png)

## Attack Selection Screen
The system displays an option of three attacks from which the user can choose. These include grid-based attack, eye occlusion attack and most significant bit attack. The user may select any one of the attacks he/she wants to perform.

![image](https://user-images.githubusercontent.com/68595241/121756301-102bab00-cb33-11eb-8aff-6d7a98d6c472.png)

## Image After Implementation of Attack
This screen shows the user the result of the attack implementation (selected by the user) on the image (selected earlier by the user). The resultant image shows how it is still perceivable by humans while a machine learning algorithm may be fooled by it.

![image](https://user-images.githubusercontent.com/68595241/121756332-29ccf280-cb33-11eb-94e6-98d431242067.png)

## Classification Results After Attack
The selected image after the attack is fed to the classification algorithm used by the system and the results are shown. Two results are shown side by side graphically. The first one shows the classification of the image by the classifier if the attack was not performed upon it. The second one shows the classification result after attack. These results are shown graphically of with what percentage confidence a certain result was predicted.

![image](https://user-images.githubusercontent.com/68595241/121756371-4a954800-cb33-11eb-8033-32869ba02791.png)

## Help Screens
On each screen, a help button is available. This also allows the user to read more about the defense and attack mechanisms employed. Moreover, it also provides instructions on how to use the system. `details.html` is help screen. It contains slideshow explaining basics of each attack.

![image](https://user-images.githubusercontent.com/68595241/121756415-6c8eca80-cb33-11eb-9f70-c0b43f8a149c.png)

