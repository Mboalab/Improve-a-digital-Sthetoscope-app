Technical document of methodology for develop a Digital Stethoscope AI 

* Motivation 
Building a digital stethoscope under $1.
Using AI for pulse rate for wide and easy adoption and use,
such as for diagnosing respiratory symptoms, and empowering doctors via telemedicine.


* Tools needed for the project 
  1- Microphone, Plug-In 
  2- Stethoscope
  3- Scissors, Free Fall

* Technologies we will used while develop the project
  1- Android studio to develop the app
  2- Emulator of Android mobile or physical Android device
  3- Machine Learning algorithms and Deep learning model to use it in the  it for sounds of pulse rate
    (for this thing, I think we need to discover the researches about "ML Model for Heart sound classification and Deep Learning Methods for Heart Sounds Classification",
   to be know perfectly with details before starting with work.. here initially I find these researches:
   - https://link.springer.com/article/10.1007/s00034-022-02124-1
   - https://www.worldscientific.com/doi/10.1142/S0217984919503214
   - https://www.sciencedirect.com/science/article/pii/S2666827021001031
   - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8229456/ )
  4- Datasets of different sound of pulse rate to classification ( such as what I found these dataset of the previous researches
   - http://www.peterjbentley.com/heartchallenge/index.html
   - https://physionet.org/content/challenge-2016/1.0.0/ )
  5- Python or any ML/Deep learning processing technique such as MATLAB(I see more of the research use it)
  6- Integration of python code(that related with ML/Deep learning technologies and algorithms) in Android studio, I found many In the youtube(I believe that YouTube is a rich resource, I found this as example https://www.youtube.com/watch?v=27kdAqDUpcE)

* what we need to do 
After reading the research, I feel that we have to deep in them to define the actual steps, but may we say,
  - Building the Stethoscope and recording sound manually (As method that in the example of the task).
  - Design the UI/UX of the app usign Figma or Lunacy.
  - Develop/Train Model of ML/Deep learning for classification of heart sound.
  - Start Developing the Android app in which (heartbeat sound will be captured/recorded through the Stethoscope then classified through the ML model connected to the code)
  