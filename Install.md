# Introduction!

Welcome! It's great to have you here. Before you start programming, let's make sure that you have all of the necessary tools that you need. This brief tutorial assumes that you have some basic knowledge of how to execute commands using the command line on mac or windows. For any questions, comments, or concerns. Please email me at [neil.nie@columbia.edu](mailto:neil.nie@columbia.edu)

# Installing
This section will cover how to setup your computer for machine learning development. 

## macOS

### Using Homebrew to install Python3

Open your command line tool (terminal) and execute these commands:

1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

2. `brew install python3`

3. `open -a TextEdit ~/.bash_profile` *Note: depending your macOS version, `~/.bash_profile` might be called `~/.zshrc` or `~/.bashrc`*

4. Now, let's add the following: `export PATH=/usr/local/bin:/usr/local/sbin:$PATH` To the end of this file we just opened. 

5. Press command+s to save the file. command+q to close the window. 

### Verify Python3 Installation

1. Open terminal and type `python3`
2. You should see 
		
		Python 3.-.- (v3.8.2:7b3ab5921f, Feb 24 2020, 17:52:18) 
		[Clang 6.0 (clang-600.0.57)] on darwin
		Type "help", "copyright", "credits" or "license" for more information.

Yours might look different, but that's ok. As long as you see Python3 in the first line. 

3. Close the terminal by pressing the control key and `D` key. Click on the `x` to close the terminal window. 

## Windows

1. Windows doesn't come with Python pre-installed. You would need to download the Python install from this website: https://www.python.org/downloads/windows/. Make sure you choose a Python 3 installer. 

2. Download the `executable installer` installer and follow the steps of the installer.  

## Installing Required Packages

Run this command to install Keras, Tensorflow, and Matplotlib

`sudo pip3 install keras tensorflow matplotlib`

# Setting up Jupyter Notebook

At this point, you should have Python3 and Pip installed. Open your terminal and execute this command to install jupyter notebook: 

`pip3 install jupyterlab`

# Try it out

Now, you should be able to launch jupyter lab by using the command `jupyter notebook` in your command line. The command should automatically launch a brower tab for you. 


## Other resources:

There are other resources that can help you to get started or debug any issues you might encounter along the way. 

Install Python3 on mac: https://docs.python-guide.org/starting/install3/osx/
Different ways to install Python3 on the mac: https://opensource.com/article/19/5/python-3-default-mac
Install Python on Windows: https://docs.python.org/3/using/windows.html#windows-full

