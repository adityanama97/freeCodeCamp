---
title: Installing and Using Python 3
---
To get started working with Python 3, you’ll need to have access to the Python interpreter. There are several common ways to accomplish this:

* Python can be obtained from the Python Software Foundation website at python.org. Typically, that involves downloading the appropriate installer for your operating system and running it on your machine.
* Some operating systems, notably Linux, provide a package manager that can be run to install Python.
* On macOS, the best way to install Python 3 involves installing a package manager called Homebrew. You’ll see how to do this in the relevant section in the tutorial.
* On mobile operating systems like Android and iOS, you can install apps that provide a Python programming environment. This can be a great way to practice your coding skills on the go.

Alternatively, there are several websites that allow you to access a Python interpreter online without installing anything on your computer at all.

---
Step 1: Download the Python 3 Installer
---
* Open a browser window and navigate to the Download page for Windows at python.org.
* Underneath the heading at the top that says Python Releases for Windows, click on the link for the Latest Python 3 Release - Python 3.x.x. (As of this writing, the latest is Python 3.6.5.)
* Scroll to the bottom and select either Windows x86-64 executable installer for 64-bit or Windows x86 executable installer for 32-bit.

---
Step 2: Run the Installer
---
Once you have chosen and downloaded an installer, simply run it by double-clicking on the downloaded file. A dialog should appear that looks something like this:

Important: You want to be sure to check the box that says Add Python 3.x to PATH as shown to ensure that the interpreter will be placed in your execution path.

Then just click Install Now. That should be all there is to it. A few minutes later you should have a working Python 3 installation on your system.

Linux
---
There is a very good chance your Linux distribution has Python installed already, but it probably won’t be the latest version, and it may be Python 2 instead of Python 3.

To find out what version(s) you have, open a terminal window and try the following commands:

python --version
python2 --version
python3 --version

If the version shown is Python 2.x.x or a version of Python 3 that is not the latest (3.6.5 as of this writing), then you will want to install the latest version. The procedure for doing this will depend on the Linux distribution you are running.

Android (Phones & Tablets)
---
If you have an Android tablet or phone and want to practice Python on the go, there are a several options available. The one that we found most reliably supports Python 3.6 is Pydroid 3.

Pydroid 3 features an interpreter you can use for REPL sessions, and it also provides the ability to edit, save, and execute Python code:

Pydroid 3 editor
---
You can download and install Pydroid 3 from the Google Play store. There is a free version and also a paid Premium version which supports code prediction and code analysis.

Online Python Interpreters
---
If you want to try out the examples in this tutorial without installing Python on your machine, there are several web sites available where you can interact with a Python interpreter online:

Python.org Online Console: www.python.org/shell
Python Fiddle: pythonfiddle.com
Repl.it: repl.it
Trinket: trinket.io
Python Anywhere: www.pythonanywhere.com

These cloud-based Python interpreters may not be able to execute some of the more complex examples in this tutorial, but they will be adequate for running most of the simpler ones and may be a nice way to get you started. More information on using these sites is presented in the next section.
