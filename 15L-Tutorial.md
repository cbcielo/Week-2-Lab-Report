# Week 2 Lab Report
Welcome to my tutorial. On this page, I will guide you through how to:

* Install Visual Studio Code
* Remotely connect to a Remote Computer
* Use some basic commands
* Move files using the `scp` command
* Set an SSH Key
* Optimize Remote Running

Follow along!

## Installing Visual Studio Code

In order to download Visual Studio Code, you must first direct yourself to the [Visual Studio Code](https://code.visualstudio.com/) website

> Note that there are different versions of VS code that should be downloaded based off of your device. This tutorial is based off a OSX (Mac) device

Once you click the link, hit the **DOWNLOAD** button and install the application on your device.

Once downloaded, open the application. You should see an a screen like/similar to this:

![Image](VSCodeHome.png)

> This is your **Homepage**.

**Congrats! You have succsessfully downloaded and installed Visual Studio Code!**

---

## Remotely Connect to a Remote Computer

The step walks you through how to remotely connect by logging into your course specific ieng 6 account.

First, click [here](https://sdacs.ucsd.edu/~icc/index.php) to find your CSE15L account log in. Follow the steps prompted  by the site to access your account. 

Open Visual Studio Code and open a new terminal.
Prompt `$  ssh cs15lsp22zz@ieng6.ucsd.edu` in the command like and press enter. 

> The "zz" in this example should be replaced by your course specific letters given by your course account

> If this is your first time connecting to a server, an authenticity message may pop up in your terminal. Type `yes` and hit enter. Then type in your password to log in.

Your terminal should look similar to this:

**Insert Screenshot**