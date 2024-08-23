# tktest
Test program for the Tkinter (and Pillow) module.

# Installing the 'pillow' module
To install the 'pillow' module, you can enter the following commands:
- `pip install pillow` if pip is located in PATH
- `python -m pip install pillow` if pip is not located in PATH
If you are running Linux, you may have to append `--break-system-packages` to install pillow, however this is not recommended, as it is better that you install pillow through your distribution's package manager.

For example, the Debian distro provides the module under the package 'python-pil'.

# Usage
If you are running the Python script, then you can run it using `python -i tktest.py`, or you can run it in an IDE (such as IDLE).

In that case, if you call a function which takes mandatory arguments (textWindow, buttonWindow and imageWindow), you will have to pass the arguments in the function instead of being prompted during execution.

If you are running one of the precompiled executables, then there are parameters you can pass:
```
Usage: tktest.py --[blank, text, button, image] --size=<width>x<height>
--blank     Open a blank Tkinter window
--text      Open a Tkinter window with a label
--button    Open a Tkinter window with a button
--image     Open a Tkinter window with an image
--size      Define the width and height of the Tkinter window.
            Default is 300x300 for all windows except --image which uses 1280x720.
```

When passing the parameters `--text` or `--button`, you will be prompted in the terminal to enter text.
When passing the parameter `--image`, a window will open up to let you select an image.
