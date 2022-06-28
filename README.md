# Construction-Safety-Equipment-Localizer
Detecting, localizing and predicting construction safety equipments using Mask RCNN with resnet50 backbone. The model is trained on self-annotated data. 
Some results from the test set are displayed below.

````
Loading weights from  /content/drive/My Drive/GarudaUAV/Mask_RCNN/logs/garuda20211220T1336/mask_rcnn_garuda_0001.h5
Re-starting from epoch 4
Processing 1 images
image                    shape: (720, 1280, 3)        min:    0.00000  max:  255.00000  uint8
molded_images            shape: (1, 1024, 1024, 3)    min: -123.70000  max:  147.10000  float64
image_metas              shape: (1, 16)               min:    0.00000  max: 1280.00000  float64
anchors                  shape: (1, 261888, 4)        min:   -0.04424  max:    0.99885  float32
````

![image](https://user-images.githubusercontent.com/32820754/165591084-201d313b-7ac3-4dc0-9181-34a26b98c151.png)

````
Processing 1 images
image                    shape: (720, 1280, 3)        min:    0.00000  max:  255.00000  uint8
molded_images            shape: (1, 1024, 1024, 3)    min: -123.70000  max:  144.10000  float64
image_metas              shape: (1, 16)               min:    0.00000  max: 1280.00000  float64
anchors                  shape: (1, 261888, 4)        min:   -0.04424  max:    0.99885  float32
````
![image](https://user-images.githubusercontent.com/32820754/165591184-590ee040-82ff-423f-b66b-cf448fa21b28.png)

````
Processing 1 images
image                    shape: (720, 1280, 3)        min:    0.00000  max:  255.00000  uint8
molded_images            shape: (1, 1024, 1024, 3)    min: -123.70000  max:  138.10000  float64
image_metas              shape: (1, 16)               min:    0.00000  max: 1280.00000  float64
anchors                  shape: (1, 261888, 4)        min:   -0.04424  max:    0.99885  float32
````
![image](https://user-images.githubusercontent.com/32820754/165591275-fddffa22-e8c4-48c5-963e-19ec8734ac77.png)



The dataset and weights are available on my Google Drive. If required, kindly reach out to me at ````siddharthmathur20@gmail.com````

