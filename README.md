# Iris-of-eyes-recognition
In this project, a Biometric Authentication system using the Iris biometric authentication method is designed. The approach taken is using the CASIA-Thousand-IRIS dataset and model it using the Deep Convultional Neural Network Architicture, with the minimum image-preprocessing such as resizing with keeping the aspect ratiio and normalization. It is an end-to-end technique without performing segmentaion of the IRIS itself. The results are promising, even without perfroing training on augmentation, the testing accuracy has reached **(91.10%)**. Finally, for the proof of the (biometric authentication system concept) a simple mobile application is designed and the model is deployed on it (IrisRecognizer) as it was exported to it's liter version were default quantization is performed.

## Model Training (Accuracy and Loss Learning Curves)
![image](https://github.com/sondosaabed/Iris-of-eyes-recognition/assets/65151701/4876ca10-0108-463d-a775-cdf7d81f18bb)

## Example of results on testing dataset
![image](https://github.com/sondosaabed/Iris-of-eyes-recognition/assets/65151701/935212e3-bc52-4f1f-b5e5-5a7ee0bc32aa)

## GUI Authenticater Module
In a biometric authentication system there has to be an authenticter part for it. A simple mobile application is done for the concept:

> Refer to this repository: https://github.com/sondosaabed/IrisRecognizer
