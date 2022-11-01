# Task 2: Design of an app for the project 
 
## Step by step methodology to  develop the mobile application
 
### 1. Requirements gathering 
#### a) Problem statement
 
The high cost of modern stethoscopes remains a significant barrier to physicians and health professionals practicing in low- and middle-income countries, 
where few affordable high-quality options exist. 
Stethoscopes, in general, are hard to sterilize resulting in a use model where cheap stethoscopes are acquired by the hospital/clinic and one is assigned to each patient, with every professional who works with that patient using the same stethoscope. 
This can result in cross-contamination as someone touches many stethoscopes. 
Cheap stethoscopes also wear out quickly and have short hoses, resulting in professionals getting physically 
closer to the patient than necessary, particularly if they have to put their arm around the patient and listen to positions on the back.
 
#### b) Objective of the project
One of the ultimate goals of the project is to come up with a complete app for pulse rate for wide and easy adoption and use.
[Sthestapp](https://www.hackster.io/mixpose/digital-stethoscope-ai-1e0229) would be an Android mobile application designed to make smartphones
an affordable yet effective solution to this issue.
 
#### c) Scope of the project
**In scope**
  - Patients can do a self check up and get a basic idea about whether they are having a particular illness/ disease or not.
  - The heartbeat can be recorded and stored for future use.
  - Stored audios can be sent to doctors through Whatsapp , Email or any other platform.
  
**Out scope**
- Developing a web application 
#### d) User identification 
- Patients 
 
#### e) Functional Requirements
- Authentication and Authorization (if needed)
- Determine whether patience is having any disease 
- Record the heartbeat and store those 
- Send recorded audios to doctors 
 
#### f) Quality Attribute Identification (non functional requirements)
- **Usability** - User friendly interfaces which anyone can understand easily
- **Privacy and Security** - Since we are storing medical details, privacy and security of the data is important. Can be achieved through using proper authentication and authorization mechanisms.
- **Accuracy** - The trained machine learning model should give accurate outputs about the disease. 
 
### 2. Requirement analysis and feasibility study
 
#### a) Technical Feasibility
 
**Technologies to be used**
- Frontend 
    - React Native or Flutter 
    *(React native is more preferable because of the ability to fast development and lower cost of development)*
    
- Backend 
   - Firestore to store recordings
- Machine learning 
   - Python along with Tensorflow framework
   - Google Cloud Platform - resources to train the model
- Other tools 
   - Figma to design wireframes and UI of the application
   - Github for version controlling and collaborating  
 
- Open source recording application will be incorporated for the recording purpose.
 
#### b) Operational Feasibility
- In developing nations android mobile phones are used by everyone and people have adequate knowledge to operate them.

#### c) Economic Feasibility
 
**Hardware tools required**
  - The bell and stem (the part which is used to check the heartbeat) of a stethoscope.
  - Mic
  - USB adaptor (if needed)
  - Android mobile phone installed our application 
 
The Stethoscope can be purchased $5 retail, the Microphone for another $5 retail. Although this adds up to $10 retail, 
we do not need most of the parts. Also, if we were to order these wholesale, we can easily cut the entire bill of material down to about $1.
USB adapters also can be very easily obtained for a cheap price.

Trail versions can be used in cloud infrastructure but depending on the server size changes might be added ( Can estimate the cost using google cloud calculator - https://cloud.google.com/products/calculator)
 
### d) Schedule Feasibility
- To provide a working mobile application meeting our requirements is achievable within the given 3 months.
 
### 3. Designing 
#### UI design
**User flow diagram**

  ![Your paragraph text (1)](https://user-images.githubusercontent.com/52100121/198849406-4da2f4c5-18c2-4441-9a5f-f3c4cde07698.png)

 **System architecture**
![OR (1)](https://user-images.githubusercontent.com/52100121/198849493-6a58bb9a-9c79-4833-8c32-0f967f4e9997.png)
 
### 4. Implementation
The implementation can be done one feature at a time. Following is the order of the feature implementation:
1. Login and registration
2. Recording audio - connect to a open source audio recording application through and API
3. Store recorded audios in firestore and access them.
4. Share recorded audios through email , whatsapp etc
5. Train the sound classification AI to determine whether there is a disease or not.
 
### 5. Testing 
Due to the time constraints manual testing can be done. If the time permits unit testing and integration testing can be done.
### 6. Deployment 
#### Deliverables of the project 
    - Hardware setup ( with Mic and stethoscope)
    - User documentation
    - Android mobile application
    - SRS document

- Mobile app will be deployed to the play store where users can download it for free of charge.

- Firebase App Distribution will used to integrate CI/CD pipeline. 

### 7. operation and maintenance 
The operations and maintenance will be driven by the community by using Mbolab slack channel to communicate while github is using as the collaboration tool. 
A well written documentation will be maintained. 
### 8.  Project Constraints and Assumptions 
Assumed that the relevant dataset to train the model will be given.
