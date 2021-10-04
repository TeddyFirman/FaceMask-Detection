## 😷 FaceMask-Detection

Project of Face mask detection, During the times of COVID-19, covering our face with a mask and maintaining social distancing is essential.
With advancements in the field of Deep Learning, now we can easily train a model and check if someone is earning a mask or not.

## 🎉 Output:

With-Mask: &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Without-Mask:


![with-mask](https://user-images.githubusercontent.com/44187690/135783844-8fd255ff-42b6-460d-8d17-8e2c6dc64927.jpeg) &nbsp; &nbsp; &nbsp;![without-mask](https://user-images.githubusercontent.com/44187690/135783884-ead9c882-ecea-4fd6-9261-70ec7d740c3f.jpeg)

## 🧠 How it works!!

- Read input either as single image or video from webcam using OpenCV.
- Detect location of faces in given frame using Face_Frontal_Default Cascade Classifier.
- Save the list of face portions for further steps.
- Load the Custom-trained CNN model, iterate each face through the model to predict mask on face.
- Post-process the frame ie; Tagging Face, with respective predictions.
