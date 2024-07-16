---
layout: page
title: Windows Installation
---
# Python Installation: Windows and MacOS

If you already have python installed on your machine, please check its version
by simply typing `python` in a command line terminal. If the version number you
see is > 3, then you are good to go. Otherwise, if you have python 2.x, then you
need to install python3 according to the following instructions. 

## Download the installer

Download the python3 install from [this
link](https://www.python.org/downloads/). Make sure to click the button below "download the most recent version".

![Download button image]({{ site.baseurl }}/assets/img/PythonInstallMac/step0.png)


## Run the installer (Windows)

Run the installer by double clicking on it.

1. On the first screen, click on `Install Now`. **However,** make note of the
   location where Python is being installed, you might need this later!

   ![Python Windows Install 1]({{ site.baseurl }}/assets/img/PythonInstallWin/01.png)

2. You should now see a green bar that is starting to fill out. Wait for it!
   Python is being installed.
3. If all goes well, you should see a screen that says `Setup was successful`.
   Click on the `Close` button on the bottom right. You are now good to go!

   ![Python Windows Install 2]({{ site.baseurl }}/assets/img/PythonInstallWin/02.png)

4. If you encountered any issues during this installation, then please reach out
   to your instructor or teaching assistant for help!

## Run the installer (Mac)
Run the installer by double clicking on it. Click through all the prompts, there are no options you should need to change.

![Installer image]({{ site.baseurl }}/assets/img/PythonInstallMac/step1.png)

Once it has completed, it will open a folder with a few items (see below). If you encounter any issues, please reach out to your instructor or teaching assistant.

![Folder opened after installation]({{ site.baseurl }}/assets/img/PythonInstallMac/step2.png)

## Test python (Windows)
To test your installation, first press the WinKey to open up the startup window,
and then type `Python`, you should see the python version show up. Click on that
icon and then type `print("Hello World!")`, you should see `Hello World` show up
in the terminal window on a new link,  looking as follows

![Python Test]({{ site.baseurl }}/assets/img/PythonInstallWin/03.png)

## Test python (Mac)
Double click the IDLE file in the folder that opened after installing python. In the command line that opens, type `print("Hello, world!")`. It should print `Hello, World!` back to you.

![IDLE test]({{ site.baseurl }}/assets/img/PythonInstallMac/step3.png)


# Git Installation: Windows

Git is a popular Version Control System (VCS) that will allow us to manage and
organize our code throughout the session.

## Download the installer

Download the Git installer [from this
link](https://git-scm.com/download/win). Make sure to click on the first link that says "click here to download the latest version" (see screenshot below).

![Git installer download button]({{ site.baseurl }}/assets/img/GitInstallWin/04.png)

## Run the installer

Run the installer by double clicking on it.

1. Click through the installation options by accepting all the defaults for each
   question (by clicking `Next`)

   ![Git Windows Install 1]({{ site.baseurl }}/assets/img/GitInstallWin/01.png)

2. On the final question, click `Install`. You should now see the green bar
   starting to fill up.

   ![Git Windows Install 2]({{ site.baseurl }}/assets/img/GitInstallWin/02.png)

3. Wait for the installation to finish and you should be good to go. Un-tick
   both buttons for "Launch Git Bash" and "View Release Notes", and then click
   on `Finish`.

   ![Git Windows Install 3]({{ site.baseurl }}/assets/img/GitInstallWin/03.png)

# Git Installation: MacOS

In order to install git, we will first need to install Homebrew. Homebrew is a package manager that simplifies installing utilities such as git. To install Homebrew, open your terminal (search terminal in Spotlight) and paste in the following:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

It may ask for a "sudo" password, if so enter the password you use to log into your computer.

Next, we need to add Homebrew to the path, which will allow us to easily run Homebrew from the terminal. At the end of the installation, you will see that it asks you to run one or two commands to add brew to the path. Make sure to copy and run these commands separately. If you need help with this, let your instructor or teaching assistant know.

![IDLE test]({{ site.baseurl }}/assets/img/PythonInstallMac/git.JPG)


Once you have Homebrew installed and set up, you can install git by running the following command in the terminal:
```brew install git```
