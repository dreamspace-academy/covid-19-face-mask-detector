Introduction
---

This covid_19_face_mask_detector is computer vision based system which gives access to people who wear face mask. There are two main sections in it. The first one is the “Management System” which is consider as the back-end. It is in written in Laravel. The “Management Panel” is used to customize the settings such as languages and etc. 

The front-end is the machine learning and computer vision part which takes care of detections and alarm voices related things. This system was programmed to make voice (vocals) in Tamil, Sinhala and English.  The language can be changed from the “Management Panel” (Back-end). 

The back-end (Management Panel) is the web-based system which keeps records of people who violet the rule by not wearing a mask. It takes snap shots and store it on the database. Then,  the admin can view those stuffs from the back-end panel. 

This system was written by many programming languages and frameworks such as Laravel, Python, PhP, HTML, JavaScript, Tensorflow, Keras, openCV and etc. This system is using MySQL database.


Installation
---
**Backend**

Setup the MySQL database which is found inside the Back_end folder, and then setup the backend (Management Panel) in a hosting server or localhost.

**Frontend**

python run_with_webcam.py




