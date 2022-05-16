# MOBL
## Introduction
* Mobile Biomechanics Laboratory (MOBL) is an open-access Android-based mobile app for undergraduate biomechanics education. 
* Students can practice real-time biomechanics analysis through this app which consists of a mobile platform-based computer-vision algorithm, a human kinematics variable estimator, and a user interface. 
<p align="center">
  <img src="https://user-images.githubusercontent.com/82116855/168656667-0586d3f3-47f7-4c13-8a63-243367374c11.PNG" width="900">
</p>
* The app includes 10 modules that can demonstrate joint angular kinematics, body segment center of mass, and jumping height. 

* For an insight view of MOBL, please refer to our paper <em>(Wang, H., Lu, L., Xie, Z., Su, B., & Xu, X. (2022). A mobile platform app to assist learning human kinematics in undergraduate biomechanics courses. Proceedings of the Human Factors and Ergonomics Society Annual Meeting.)</em>.
* **GITHUB use:**
  1. For windows user, click 'Code' in green button and select 'Download Zip'. Where you download it doesn't matter.
  2. Open the zip file and unzip it.
  3. The files in the zip file are exactly the same with the files shown in the Github page. Follow the following instructions for the use of code.
* **Usage:** 
  1. Download the data. (Marker data/Videos were stored as .mat/.avi)
  2. Extract the data under folder '\data'. Note that the code used one sample from Sub07 for demo purpose.
  3. The following graph shows the **data structure of a single trial of marker data (.mat file).** You can also run though the file 'basic_functions.m' block by block for the details. For the data structure of txt file, please refer to the 'readme.txt' attached with the txt data.\
  <img src="https://raw.githubusercontent.com/LLDavid/MOPED25/master/image/data_structure.png" width="500">\
  4. **Important:** The video file is 30 Hz and the motion data is 60 Hz. Therefore, each video frame has two corresponding motion frames.
