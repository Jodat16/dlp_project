# dlp_project

## CNN Model (MobileNet)

### Load Data
![image](https://github.com/Jodat16/dlp_project/assets/89530816/54c552d7-cca1-42b2-882f-526b63c8146b)

### Get MobileNet with trained weights in ImageNet dataset exclusing top layer
![image](https://github.com/Jodat16/dlp_project/assets/89530816/f2b13580-6e82-4f3e-a46f-4f4db2f0a97e)

### Add Flatten layer for to bridge convolved images to dense layer
![image](https://github.com/Jodat16/dlp_project/assets/89530816/5e245af0-e21d-462d-b2e3-6a072bba94b3)

### Compile model with following parameters:
loss='categorical_crossentropy'
optimizer='adam'
metrics='accuracy'
![image](https://github.com/Jodat16/dlp_project/assets/89530816/6e0cd42f-164b-4ed1-83bb-363ae8f172e3)

### Use ImageDataGenerator function for resizing and augmentation of Input images
![image](https://github.com/Jodat16/dlp_project/assets/89530816/d9473538-395d-4fe3-a456-2fb80f68fe82)

### Trained model over 10 epochs and batch size of 32
![image](https://github.com/Jodat16/dlp_project/assets/89530816/135be0ca-2695-4a0b-a082-0de99e50e3ad)

### Loss and Accuracy graphs against epochs
![image](https://github.com/Jodat16/dlp_project/assets/89530816/5a3015f0-c573-4759-bb95-2361a7928c79) ![image](https://github.com/Jodat16/dlp_project/assets/89530816/bb44532f-5f74-4ad0-b21f-0fb527355651)

### Confusion Matrix and Final Accuracy
![image](https://github.com/Jodat16/dlp_project/assets/89530816/8a02fd01-5608-485a-912f-335d0a57b1d7)
![image](https://github.com/Jodat16/dlp_project/assets/89530816/088d3fef-b4dd-4013-bef3-3c7284e5a184)

### TPR, FPR, TNR, FNR
![image](https://github.com/Jodat16/dlp_project/assets/89530816/16ea8837-e7f9-4f49-95e5-f2d0a0282453)







