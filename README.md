# CAC Segmentation
The above notebooks are my latest work Segmentation of Heart Calcifications Segmentation and CAC Scoring. The model used a Novel Single step 3D Diffusion-Net with seperate Modality and Noise Encoders trained on a combination of Dice, BCE and MSE. 
<img width="638" height="397" alt="image" src="https://github.com/user-attachments/assets/3e1bd37a-e46a-4414-9f6c-c23b44e74d6d" />
Fig. An overview of Model Architecture


<img width="622" height="528" alt="image" src="https://github.com/user-attachments/assets/5818adb7-5f08-4e2e-9077-9f2c2ee347af" />
FIg. A detailed structure of Model Architecture


The model performance was on par with SOTA segmentations models for the given dataset, while being significantly smaller i.e. lesser parameters.

<img width="677" height="265" alt="image" src="https://github.com/user-attachments/assets/be116be1-dede-41b5-9b6f-85ce6ab8686c" />
The dataset used was the Stanford's COCA Dataset.
