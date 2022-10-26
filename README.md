# Skin-Lesion-and-Wound-Segmentation
Determined lesions and wounds’ outline by semantic image segmentation in Dermoscopic and Medical images using and modifying various deep learning architectures to overcome certain specific challenges like low contrast, obscure lesion boundaries
etc in medical images.</Br>
Obtained Dice coefficient as high as 93.75% on certain datasets and concluded which architecture and loss function performs
better on a particular medical dataset.</Br>

# Learning curve and Progress
* Fundamental of Deep Learning - Backpropagation, Convolution, Pooling, Activation Functions, etc. </Br>
* Evaluation Metrics - Accuracy, Precision, Recall, IOU, DSC </Br>
* Image Segmentation Models - UNet, SegNet and Deeplabv3 (for ISIC 2016 Skin lesion segmentation) </Br>
* Class Activation Maps - GradCam and ScoreCam (using VGG16 on a Kaggle dataset) </Br>
* Selected some Medical image segmentation datasets - DRIVE, Foot Ulcer Segmentation, COVID19 - I, COVID19 - II, ISIC 2016 & Cardiac MR  </Br>
* Computation of results using baseline segmentation models and their comparison </Br>
* Developing insights - Focused on improving accuracy by understanding input parameters and model architecture </Br>
* Paving way for future improvements on various datasets using the knowledge gained </Br>

# Results and Highlights 
![image](https://user-images.githubusercontent.com/71214127/197967196-78b93ebb-32e9-4690-9a4f-18bc165faedb.png)
![image](https://user-images.githubusercontent.com/71214127/197967312-fe930891-f524-4c42-bd4a-3a3d88af9f81.png)
![image](https://user-images.githubusercontent.com/71214127/197967375-86744e18-ab94-4d8c-a271-0a24b1be24e6.png)
![image](https://user-images.githubusercontent.com/71214127/197967464-5eea161c-d83d-4256-881d-d60e57aeb826.png)
![image](https://user-images.githubusercontent.com/71214127/197967559-a8735fb1-358a-48ad-af9e-fcdb7142034b.png)
![image](https://user-images.githubusercontent.com/71214127/197967811-83d7fcd8-d677-4831-933a-83d40fa367b1.png)
![image](https://user-images.githubusercontent.com/71214127/197967886-55f6b168-8f52-4dab-8fae-e4fac2efc1c9.png)
![image](https://user-images.githubusercontent.com/71214127/197967974-e12affbc-b2e7-4aa5-b64b-42e2f2f29093.png)
![image](https://user-images.githubusercontent.com/71214127/197968075-8693d846-0c63-4d77-afde-8be55e229323.png)
![image](https://user-images.githubusercontent.com/71214127/197968132-e87f48a4-9191-486f-a86f-f8f88a1b03f1.png)
![image](https://user-images.githubusercontent.com/71214127/197968233-1843b18b-02a8-4711-80dc-845a39b15fd7.png)
![image](https://user-images.githubusercontent.com/71214127/197968291-c15d7cf4-6192-44ca-b0bb-279b3d6b8d8c.png)
</Br>
# Future Work  
As we’ve understood  layer-wise input parameters of the various segmentation models, we plan to perform model wise parameters’ comparison on more medical segmentation datasets in order to look into scope of improvement in any of the architecture</Br>
Look into tools for improvement of segmentation results as Class Activation Maps (CAMs) does for the image classification problem since the explainability in segmentation problems is comparatively less explored.</Br>
In future, we plan to dig deeper in comparing  various baseline models results with type of medical dataset as to get an estimate of which model will perform better by doing some qualitative(image shape, type, etc.) analysis of the training and the test data’s images.</Br> 


