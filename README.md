# Quantitative-Analysis-of-Blood-Cell-Components-and-Detection-of-Malarial-Parasite(P Vivax) using-Faster-R-CNN

This project introduces an advanced automated system utilizing the Faster R-CNN 
architecture for precise detection of red blood cells (RBCs), white blood cells 
(WBCs), platelets, and the malarial parasite Plasmodium vivax in blood smear 
images. To enhance our dataset, we employ two types of Generative Adversarial 
Networks (GANs)-one to generate new, diverse images and Real ESRGAN to 
improve the resolution and quality of these images, thereby increasing the 
robustness and performance of our system. Aimed at aiding medical professionals 
in diagnosing blood disorders and malaria, our system provides rapid and reliable 
microscopic sample analysis. Extensive experimentation confirms our method's 
efficacy in accurately identifying various blood components and malaria parasites, 
demonstrating its potential to revolutionize medical diagnostics and significantly 
improve patient outcomes in hematology and infectious diseases.

The Blood cell dataset has been taken from the Shenggan BCCD dataset available on Github. 
The malarial dataset consists of the Plasmodium Vivax parasite within the images which can be found in 'malaria_images.zip' file.
Blood cell images generated using GANs and the enhanced resolution using Real-ESRGAN can be found in 'Real-ESRGAN Enhanced Blood cell dataset.zip' file.

![image](https://github.com/mai420/Quantitative-Analysis-of-Blood-Cell-Components-and-Detection-of-Malarial-Parasite-using-Faster-R-CNN/assets/99639678/10a7dbc1-8a24-4b45-95a4-eedce229e6dd)
![image](https://github.com/mai420/Quantitative-Analysis-of-Blood-Cell-Components-and-Detection-of-Malarial-Parasite-using-Faster-R-CNN/assets/99639678/9963f087-b8b7-4b5e-b3e9-d59288e3f380)

The Faster R-CNN codes for the mentioned datasets is given by:
BCCD dataset is available in 'FRCNN_RBC_WBC_PLATELETS.ipynb'
Malarial dataset is avaiable in 'malaria_red.ipynb' 
GAN generated images on the BCCD dataset is available in 'BCCD+GAN.ipynb'

The GAN code which is being used to generate 64 new images of the blood cell components is given in 'GAN.ipynb'
Real-ESRGAN is used in the project to enhance the quality of the GAN genrated images whose code is given in 'Real-ESRGAN-Sber.ipynb'
