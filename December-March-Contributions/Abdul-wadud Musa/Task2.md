


REQUIREMENT : Digital Stethoscope AI 


****************************************************************************************************

EXPECTED OUTPUT : A well functioning and interactive Digital Stethoscope application

****************************************************************************************************

COMPONENTS : 
- Hardware Components :
    1. Stethoscope
    2. Microphone Plugin

- Software Components : 
    1. Android Studio
    2. Figma
    3. Trained Model for heartbeat classification
  
****************************************************************************************************

The application would be written in kotlin, following the single activities and lots of Fragment 
recommendation by google. 

Libraries to be used in the project include 
- Navigation Component & Jetpack Libraries  (https://developer.android.com/guide/navigation/navigation-getting-started)
- Retrofit(https://square.github.io/retrofit/)
- Material Design Component  (https://m2.material.io/components)
- Moshi (https://github.com/square/moshi)
- Room Database (https://developer.android.com/training/data-storage/room)
- Hilt 
- Compose 



Navigation Component would be used to handle Navigation within the application, Retrofit would
be used to send over the audio file recorded from individual heart beat to the backend server, To 
ensure a very good user interface and experience the user interface of the application shall be 
developed following material Design guideline. Moshi Library would be used for converting from 
JSON response to a kotlin class object. Room Database would be used to store user recording to avoid 
having to record heartbeat again when there is an issue with the internet. Hilt would be used for 
dependency injection. Compose would be used to write the user interface 


****************************************************************************************************

The application would use the MVVM design pattern and use a clean architecture. 
(https://developer.android.com/topic/architecture?gclsrc=ds)
