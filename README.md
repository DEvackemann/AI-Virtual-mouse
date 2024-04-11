# AI-Virual-Mouse

AI-virtual mouse: a software marvel utilizing web cameras for mouse input, bypassing physical peripherals. Powered by Python libraries like OpenCV and PyAutoGUI, it offers seamless control through hand detection, numerical processing, and mouse emulation. With its advanced capabilities, it transforms user interaction, promising a future of intuitive computing.

### Detecting which Fingure is Up and Performing the particular Mouse Function
![img](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/e0619a4a-1334-42b7-8b78-701fe200f143)

## How to setup and run

  install
  Python: (3.6 - 3.8.5)<br>
  Anaconda Distribution: To download click [here](https://www.anaconda.com/anaconda-navigator).
  
  Download and Extract the Project Folder Name AI-Virtual-Mouse.<br>
  And then Open the AI-Virtual-Mouse Folder in VsCode 
  
  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
  
  Step 2:
  ```bash
  conda activate gest
  ```
  
  Step 3:  
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
   cd src
  ```bash 
  python Virtual_Mouse.py
  ```
note :
1.Open Anaconda Navigator.
2.Launch Visual Studio Code (VSCode) from the Anaconda Navigator interface.
3.Prior to executing any code, ensure you are in the correct directory example (C:\Users\dubey\AI-Virtual-mouse\src> python virtual_mouse.py) by verifying your current directory location.
### Output:
1. No action performed : When all the five figures up then the cursor will stop moving.
![1st](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/749c94f6-581d-4b5e-b425-4d41f679160f)

2. Cursor Moving: When both index and multiple fingers up.
![2nd](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/204c2052-fca3-4d83-b9f4-fbca18093208)

3.Left Button Click: Lower the index finger and raise the middle finger
![3rd](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/e280606c-4a01-46cb-aa3e-d93c01a252d9)

4.Right Button Click: Lower the middle finger and raise the index finger.
![4th](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/b1050583-2f1f-46a9-bd75-d7f93aa69022)

5.Brightness Controll: Make pinch of index finger and thumb and raise all the rest of fingers and move hand horizontally.
![5th](https://github.com/DEvackemann/AI-Virtual-mouse/assets/150266045/81f9a843-0dfa-48f2-ae8a-8c7e470bd7fc)

#### Made with ❤️ by Anshika Dubey
