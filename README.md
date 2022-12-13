# Replacing You

--- 
Project with OpenCV and Python.
Our project name is Replacing You. It's a program that replaces a person with a picture when you deviates from the camera frame in webcam.
Idea by Rkyungdeok and made by OpenSource team 29.


# Key points

***1. Connecting camera***
- connecting with webcam and reading the webcam
- when cannot read webcam " There is no camera " phrase is printed
- when read webcam, output into window called 'test'

***2. Detecting face***
- haarcascade_frontalface_default.xml
- detect_face.py to marking face with square

***3. Detecting face in different aspect***
- haarcascade_profileface.xml

***4. Loading a image from User***
- a picture needed to substitute user's face when out of frame

***5. Replacing with picture***
- when a user is out of frame, replacing with picture that is get from user

# Used package and reference
**1. haarcascade_frontalface_default.xml to detect frontalface**
- Download from Github at [*official Github site address*](https://github.com/opencv/opencv/tree/master/data/haarcascades)

**2. haarcascade_profileface.xml to detect sideface**
- Download from Github at [*official Github site address*](https://github.com/opencv/opencv/tree/master/data/haarcascades)
- Reference from OpenSource Lecture week 13 ppt by Prof.Youngmin Oh

**3. detect_face.py haarcascade_profileface.xml to detect sideface**
- Reference from OpenSource Lecture ppt by Prof.Youngmin Oh

# Results
**Results After Python connect_carmer.py**


![temp_1670926862845 -1833651748](https://user-images.githubusercontent.com/113025040/207292573-8fc1a459-09db-4ea1-a87d-0a1a44b33f4e.jpeg)

**The result of executing the connect_camera by excluding the symmetrical part**


![temp_1670926873461 -493618965](https://user-images.githubusercontent.com/113025040/207294540-9cc6abbd-688f-49e7-9dde-cf95a279d32b.jpeg)

**detect_face.py execution result**


![temp_1670926892379 1567086311](https://user-images.githubusercontent.com/113025040/207294560-d28ef98c-4c31-4a5f-9d17-57b0b8aba75c.jpeg)

**An image that comes out when you don't show your face**
