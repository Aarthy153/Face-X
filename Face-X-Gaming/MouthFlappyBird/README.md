# FlappyBird Mouth

## Intro

**FlappyBird Mouth game** is a Image Processing topic, written in Python using image processing techniques to detect mouth and mouth open/close states to control the game play.

This project focuses on the Image processing part, the game Flappy Bird is just to demo the Image processing part.
The code for Gameplay of FlappyBird is based on https://github.com/0-whatsis-1/FlappyBird-using-Eye-Blink.

In this project, dlib's face detector(HOG-based) is used to detect player's face and the facial landmark predictor is used to detects mouth of the player. Then a mouth aspect ratio will be calculated to detect if the mouth is in OPEN or CLOSE state. If in OPEN state, the game will trigger a jump action of the bird.

---

## Installation of Dependencies

- First run command below to install dependencies. 
    - If you are using python 3.7, run command:
            pip install -r requirements-3.7.txt
    - If you are using python 3.8, run command:
            pip install -r requirements-3.8.txt

- If installing `dlib` or `cmake` dependencies has problem, please refer to the official documentation of the toolkits:
    
    - For Cmake download and install from [Cmake](https://cmake.org/download/)
    - For [dlib](https://github.com/davisking/dlib) or [follow] (http://dlib.net/compile.html) for guidelines on how to compile

---

## To run the Project

- Run the file main.py in the terminal 
        python main.py
or run file main.py from any python IDE.
