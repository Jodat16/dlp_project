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

## Vision Transformer for image Classification

### Import necessary libraries
![image](https://github.com/Jodat16/dlp_project/assets/89530816/2071f9e6-b484-4b2c-a8c3-c961d7270d90)

### Set batch size and learning rate, also check for GPU if available
![image](https://github.com/Jodat16/dlp_project/assets/89530816/84074795-e04f-4efb-b308-039fa44cc519)

### Image preprocessing
##### Transform images to tensors and resize them to an input size of (224,224)
![image](https://github.com/Jodat16/dlp_project/assets/89530816/a14f260c-c2a2-4812-8d71-e18df4e8c5e0)


### Load Data into train and validation Data loaders
![image](https://github.com/Jodat16/dlp_project/assets/89530816/80110886-8dad-4fdb-946a-eb22af0d1a0e)

### Display an image from each class
![image](https://github.com/Jodat16/dlp_project/assets/89530816/d2c45805-ebb7-44eb-82d0-8026eab77f96)
![image](https://github.com/Jodat16/dlp_project/assets/89530816/d622a980-5005-447f-a364-c356805421f5)

### Build Transformer layers
![image](https://github.com/Jodat16/dlp_project/assets/89530816/dc1bea92-27a3-41be-96b5-7810dfd24177)

### Train model
![image](https://github.com/Jodat16/dlp_project/assets/89530816/2d87a329-9f5b-4a10-8186-6d566cb105fa)
![image](https://github.com/Jodat16/dlp_project/assets/89530816/e5e52273-ed14-4ddc-b234-8d8c17e622e8)

### Loss and Accuracy graphs against batches
302 batches * 6 epochs

![image](https://github.com/Jodat16/dlp_project/assets/89530816/8e9b1b82-4a1b-4fa3-a00c-61449835a02d)

### Final Accuracy
![image](https://github.com/Jodat16/dlp_project/assets/89530816/d7166a85-5b9f-47e3-8b9b-fe5b4c403989)

![image](https://github.com/Jodat16/dlp_project/assets/89530816/bf46d411-3ebc-4ddb-80e6-e2dcf7f8f915)








