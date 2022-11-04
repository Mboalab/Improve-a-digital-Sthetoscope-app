# Design of an app for the project

## Aim of this task:
To create a technical document with a detailed list of tasks, descriptions, and tools needed to develop a similar app

## Tools to be used for this project
Hardware tools:
- Microphone
- Stethoscope
- Universal adapter

Software tools:
- Cloud-hosting platform: Google Cloud Platform
- AI/ML stack: Python (TensorFlow)
- App development: Android Studio
- Mobile app-hosting ML service: TensorFlow Lite

Other tools:
- Scissors
- Free fall

## Introduction:
The high cost of modern stethoscopes remains a significant barrier to physicians and allied health professionals practicing in low- and middle-income countries, where few affordable high-quality options exist. Stethoscopes in general are hard to sterilize resulting in a use model where cheap stethoscopes are acquired by the hospital/clinic and one is assigned to each patient, with every professional who works with that patient using the same stethoscope. This can result in cross-contamination as someone touches many stethoscopes. Cheap stethoscopes also wear out quickly and have short hoses, resulting in professionals getting physically closer to the patient than necessary, particularly if they have to put their arm around the patient and listen to positions on the back. <br>
This app is aimed at limiting the prolonged contact of the nursing staff with the patient and to have a device which can be placed by the patient but interpreted by the practitioner. <br>

Telemedicine apps, such as this digital stethoscope app, have (and will) gone a long way in being efficient in the medical sector. This helps us to deliver care from our various locations. This is very satisfying, as a lot of persons would gain free access to healthcare via technology.

## Methodology
The methodology of building the app could be divided into three major steps:
#### Step 1: Data collection and preparation
The stethoscope and the microscope are needed for the collection of the sound data. 

![image](https://user-images.githubusercontent.com/69730153/199153200-a2c01d20-2a00-44be-834e-0dde7d018ae8.png)

First, the stethoscope is gotten, and its lateral end (that is, the scope) is cut and set aside. The scope is attached directly to the small microphone (image below). This would allow the sound generated to go directly to the microphone. The sound is then recorded. It could be recorded via a phone or computer. In developing nations, phones are much more common for recording. A USB adapter could be used to attach the microphone and scope connection (as seen in the image below).

![image](https://user-images.githubusercontent.com/69730153/199153278-07e9388b-48da-4c7c-a9d7-ba1cd2c52318.png)

#### Step 2: Training the ML model
In this step, we would build a classification model.
The data is to be trained on the cloud using the Google Cloud Platform. It has most of the prerequisites installed, and we can go straight into modification in the ubuntu system itself. We will be working with a modified version of the speech command example.

#### Step 3: Deployment
To run on Android, the easiest way is to first run tflite file.
TensorFlow Lite is an open-source software library for mobile and embedded devices. 
Once we have tflite file, we can load it into voice classification from tflite app. So after everything is done, an open-source recorder or any other recorder can be used to record and send the voice files to the doctor. For a check on conditions remotely by a doctor, they can simply plug it into a microphone jack and use it for remote diagnosis.


## Precaution
One way to achieve a higher model accuracy score (anything greater than 90% is an excellent score) is to work with a larger dataset. Therefore, we would have to collect thousands and thousands of data.


## Conclusion
In conclusion, the software tools needed to develop this app include:
- Cloud-hosting platform: Google Cloud Platform
- AI/ML stack: Python (TensorFlow)
- App development: Android Studio
- Mobile app-hosting ML services: TensorFlow Lite 

On the other hand, we could also explore the use of Google Colab, also hosted on the cloud, to train the data.
Furthermore, we could upload the app on Google Play.

