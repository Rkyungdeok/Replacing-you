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
- Reference from OpenSource Lecture week 13 ppt by Prof.Youngmin Oh

# Results


![temp_1670926862845 -1833651748](https://user-images.githubusercontent.com/113025040/207306656-53a1716a-72e6-452f-a184-426f340b21e4.jpeg)


![temp_1670926873461 -493618965](https://user-images.githubusercontent.com/113025040/207306664-d86f602c-4e2b-44fe-add1-355571a1d3f6.jpeg)


![temp_1670926884032 -376915748](https://user-images.githubusercontent.com/113025040/207306670-458004e1-8c26-4129-8c2e-1dafe8f58ab2.jpeg)


![temp_1670926892379 1567086311](https://user-images.githubusercontent.com/113025040/207306677-43a5bf7e-395a-4f98-b11c-9b8c67f99bbe.jpeg)
