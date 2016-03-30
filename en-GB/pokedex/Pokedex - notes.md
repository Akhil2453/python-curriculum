---
title: Pokedex — Volunteer Notes
---

#Introduction:
This project teaches children how to make a graphical user interface (GUI), by making a Pokedex for displaying information on Pokemon. This project accesses the <a href="http://pokeapi.co/">pokeAPI</a>, developed by <a href="http://phalt.co/?ref=pokeapi">Paul Hallett</a>.

#Resources
For this project, Python will need to be installed. It is recommended that version 3.2 of Python is installed.

Children will need to use of the materials which accompany this project. Files included in the 'Project Materials link:

+ GUI.py (short example program)
+ pokeapi.py (module used for retrieving data)

Make sure that each child has read and write access to their own copy of these resources.

You can find a completed version of this project's challenges by clicking the 'Project Materials' link for this project, which contains:

+ pokedex-finished.py
+ pokedex-finished-with-images.py
+ pokeapi.py (module used for retrieving data)

#Learning Objectives
+ Graphical User Interface elements (widgets):
	+ Text boxes;
	+ Labels;
	+ Buttons.
+ Customising widgets with the `.config()` method;
+ Using buttons to execute functions and update widgets.

#Challenges
+ More widgets - adding widgets to a GUI window;
+ Making widgets look nice - changing widget look and feel, using the `.config()` method;
+ Finishing your Pokedex - dynamically changing label values within the program.

#Frequently Asked Questions
+ Make sure that children have a copy of the `pokeapi.py` file, and that it's saved in the same place as the program they are writing!
+ When the GUI program is run, the GUI window may be hidden behind the Python shell window. Minimising the shell should reveal the window!
+ If you're having trouble installing the Python Image Library (PIL) module, the rest of the project can still be completed, but you'll have to remove the parts of the `pokeapi.py` file that reference the PIL. The parts of the code to remove are marked in the file.
+ Only .gif images can be displayed in a GUI window. For the optional 'Adding an image' section of the Pokedex, the <a href="https://pypi.python.org/pypi/Pillow/2.2.1#downloads">'pillow' module</a> will need to be installed. You can test whether you have pillow installed, by simply running `from PIL import Image`. If no errors are returned, then it should work!