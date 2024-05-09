# dlp_project

## CNN Model (MobileNet)

### Load Data
![image](https://github.com/Jodat16/dlp_project/assets/89530816/18b5a18d-024b-4864-900e-dabf7999754c)

### Get MobileNet with trained weights in ImageNet dataset exclusing top layer
![image](https://github.com/Jodat16/dlp_project/assets/89530816/e161a9d3-c96e-4dd3-b719-598a66a28104)

### Add Flatten layer for to bridge convolved images to dense layer
![image](https://github.com/Jodat16/dlp_project/assets/89530816/d6e35d90-a144-408c-b986-33ce672cc313)

### Compile model with following parameters:
loss='categorical_crossentropy'
optimizer='adam'
metrics='accuracy'
![image](https://github.com/Jodat16/dlp_project/assets/89530816/5f24583b-b960-4900-9892-584514b65f4f)


### Use ImageDataGenerator function for resizing and augmentation of Input images
![image](https://github.com/Jodat16/dlp_project/assets/89530816/f1820590-b042-4d5f-a12d-c1eddc2ebb33)

### Trained model over 10 epochs and batch size of 32
![image](https://github.com/Jodat16/dlp_project/assets/89530816/f8869534-d93d-4d87-acfc-d4ed0c5dd925)

### Loss and Accuracy graphs against epochs
 ![image](https://github.com/Jodat16/dlp_project/assets/89530816/16a41b90-3402-4c37-a8f0-1455b4eb0d42) ![image](https://github.com/Jodat16/dlp_project/assets/89530816/5e245516-e20a-4723-a009-6b785f058ad0)


### Confusion Matrix and Final Accuracy
![image](https://github.com/Jodat16/dlp_project/assets/89530816/3772f0f9-4370-488d-b990-d992953d054f)

![image](https://github.com/Jodat16/dlp_project/assets/89530816/d136e85d-a9ca-443f-8731-9bbb469d61bc)


### TPR, FPR, TNR, FNR
![image](https://github.com/Jodat16/dlp_project/assets/89530816/963c7820-35a3-42da-9e7c-c688d4e0085a)







