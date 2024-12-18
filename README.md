## Simple Face Recogniition

A Simple Face Recognition is a technology used to detect and identify human faces in images or videos by comparing them to a database of known faces. In this system, a webcam captures real-time video frames, and a pre-trained face recognition library processes these frames to locate faces and extract unique facial features (encodings). The system matches these encodings against a database of pre-encoded images to identify individuals, providing their names and accuracy scores. Using image processing techniques like resizing and color conversion, it enhances performance while maintaining accuracy. The results, including bounding boxes and labels with names and confidence percentages, are displayed on the video feed. This technology has applications in security, personalized systems, and automated attendance.

## Install

### Install on Windows

Install [Git Bash](https://git-scm.com/downloads) and [Python](https://www.python.org/downloads/) first

After that, open git bash and follow these commands

```bash
$ https://github.com/JosuaLimbu/face-recognition.git
$ cd face-recognition
$ pip install -r requirements.txt
$ python3 main.py
```

**And the result, when the face is recognized and exists in the database, is shown like this.**

![result1](result/Screenshot1.jpg)

**And the result, when the face is not recognized and does not exist in the database, is shown like this.**

![result1](result/Screenshot2.jpg)
