# Pneumonia_healthcare
In this Project, I have preprocessesed the images as to avoid differ resolution, contrast, size,to have a final (1024, 1024) size, I am using here tenserflow, numpy, openCV, sklearn module and by using deep leaning sequential model from keras.model under the tensorflow, after trainig for 50 eopch with batch size 74. I am able to train the model on 1127 CXR normal, and 995 CXR Pneumonia images, and a validation dataset combined of normal and Pnemonia CXR images.
SO here i am clas i am getting the accuracy as 63.4% as the model accuracy and the xtest i.e testing accuracy is 80%, after saving the model to mounted drive.
Morely, here we are saving the CLASSIFICATION values of CXR as 0 vs 1, in ytest vs ypred in csv submission file.
