# about project
connect ml kit on firebase
login or signup on firebase
in forebase create new projecy
go to tools - firebase- analytics- connect with firebase- choose project from dialog box- click connect

to include ml kit dependency in app:
gradle scripts- build.gradle(module.app) : add google services dependency & sync project

1.designing ui
2. facedetection.java class
   1. firebasevision : open camera on real device & enabling face detection
   2. firebasevisionfacedetector
   3. performance mode : speed or accurancy
   4. detect landmarks : facial landmarks identity eyes,ears,nose
   5. detect counters : facial features
   6. minimize size : enable face tracking
   7. after img captures ml kit provides bitmap
   8. FirebaseVisionFaceDetector : config face detection model
   9. FirebaseVision image object : bitmap & pass inot model
   10. firabase mlkit aims to make ML more accesible by providing a range of pretrained models

# firebase realtime database:
1. cloud hosted db
2. it runs on cloud & access to user is provided as service
3. stores data in JSON format
4. all the users connected to firebase get access to realtime data

# firebase ML kit
1. provides features: text recognization
2. img labeling
3. landmark recognization
4. face detection
5. translation img labeling & tracing object 
# Face-Detection_App![WhatsApp Image 2022-06-23 at 12 38 56 PM](https://user-images.githubusercontent.com/91388114/175237499-1e6b9d3e-5ffb-443d-abb0-67e3f8126bd5.jpeg)
![WhatsApp Image 2022-06-23 at 12 38 56 PM (1)](https://user-images.githubusercontent.com/91388114/175237507-dd013ec9-58d5-49dd-a9f5-94806b2f345b.jpeg)
