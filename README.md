# RaspberryPi Face and Object Detection DoorLock
I am using RaspberryPi to hold the ML model I build and it will work as a Security Door Lock


## Project Components
- **Face Recognition**
  - Using Tensorflow Building a customized Siamese Model for One-Shot Learning 
  - Using Roboflow and Google Colab to gather Anchor, Positive for User(Me & My family). Negative using lfw dataset
  - Recognize my or my family's faces or identify as a Stranger
  
- **Object Detection**
  - Using Yolov5 with customized dataset created in Roboflow
  - Detect nearby objects after Face Recognition failed to identify a user in database
  - Identify objects like packages, presents, or dangerous objects to send a relative message to my Phone
  
- **RaspberryPi 4B**
  - Using RaspberryPi to hold both ML models
  - Attach with a Camera Module
  - Attach with a Servo to lock the door
  
- **3D printing**
  - Using Solidworks to CAD the case for holding a 15000wAh battery charger, RaspberryPi and the Camera
  - 3D printing the STL files in School
  
  
## Future Ideas
- 3D print a gimbal and attach a better camera
- Use bluetooth module in RaspberryPi to recieve data transmitted from camera
- Use Actuators to lock the door better
