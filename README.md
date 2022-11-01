# EyelidNet
## Vitaly Lerner , 2022

The purpose of this project is to generate sets of images with traced eyelids. 

# Installation
The main file is EyelidNet_Manual.py
The following packages are required:
- numpy
- tkinter
- matplotlib
## Separate environment
If needed, create a separate python environment (let's call it `eyelid`)

1. Open  Anaconda Prompt (skip to 3 if no separate environment needed)
2. `conda create -name eyelid python=3.8 numpy  matplotlib`
3. `conda activate eyelid`
4. `conda install numpy matplotlib`
5. `conda install -c conda-forge tk`


Run the program by 
`python EyelidNet_manual.py`
![explanation image](Explanation2.png)

# Marking eye lids with the program
1. `cd <path to the the directory with EyelidNet_manual.py>`
1. Download the images and put them in a certain folder *<path_to_folder>*
1. Press **Images folder...** and navigate to the *<path_to_folder>*
1. If first time, press "New Session" and create a session file, preferably not in the *<path_to_folder>*
1. Press **Work on current Image**
1. Select 8 points as shown here . **!!!ORDER MATTERS!!!**:
![explanation image](Explanation.png)
How to work with the mouse:
- Left click to select a point, 
- Right click for "undo"
- Do not press the middle button
- **If zoom in needed, right click after the zoom in, otherwize, a point will be created at the top left corner of the zoom region**
1. If you're satisfied with the result shown on the main window, click "Work on Next Image"
Otherwise, repeat the current image with **Work on current Image**
1. If you're tired, just close the window
1. To continue from the point of the break, open the program, and instead of **New Session**, use **Load Session**

# Finilizing the result
The results will be stored in the session file. This is a csv file. Please upload it/send it by email.
