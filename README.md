# ImageLabeler
A simple and light weight Python Kivy based software tool to label the multiclase images contained in a folder to class folders. This tool is best suited for image labeling/annotation for classification problem.

-----

# Requirements 
Tested on Windows 10 <br>
Python >= 2.7 <br>
Kivy >= 1.0.6

Tested on Ubuntu <br>
Python >= 3.9.7 <br>
Kivy >= 2.0.0

-----

# Installation procedure

Step 1: Install Python. It is important to have the right version of Python. To check the correct version of Python, we have the command
'pyhton -- version'
It is important to have the right version of python as detailed in the link below:
https://kivy.org/doc/stable/gettingstarted/installation.html#install-pip

Step 2: Install kivy using the pip library. 
Command: 'pip install kivy'

Step 3: Execute the main.py file on the corresponding terminal. Ensure that the folder is pointing to the right path


-----


# Usage
Folder containing large pool of images (change required): 
`sourceImageFolder = 'foldername'`

Class folder names and their respective keyboard shortcuts (change required):
```
key_dict = {
    'w': 'Folder 1',
    'a': 'Folder 2',
    's': 'Folder 3',
    'd': 'Folder 4',
    'f': 'Folder 5',
    'g': 'Folder 6',
    'u': 'Folder 7',
            .
            .
            .
    
    'q': 'Folder n',
    'e': 'Folder n+1',
}
```

Keyboard shortcuts:
`'w', 'a', 's', 'd', 'f', 'g', 'u', 'q', 'e'`
