# Powershell-Capture-Screenshot
--------------------------------

Introduction - Capture-Screenshot:
---------------------------

Below details explains the entire scenario in creating the image that contains the screen content, like the windows and other details on the screen. Each time the application will run, it will save the image inside your Documents folder where you can acces


Background
----------

This script was designed for one the usecase where the screenshot of existing running application and services was required as a part of daily health-check of their existing system, the screenshot will be required to sent on email to respective team.


Assemblies Required
-------------------

Following namespaces is required to be called for this project:

using System.Drawing; 
using System.IO; 
using System.Windows.Forms;

System.Drawing
This namespace is required for the Graphics, Bitmap etc. Without this they won't work and you will get an error by the IntelliSense saying this is not found.

System.IO
This namespace is required to save the (image) File. As the name states it is a namespace for the Input/Output commands. Saving, deleting files inside the file system is done using this!

The remaining code is just a simple Console application to check for the details on the screen and convert them to the Graphics to save inside a PNG file. 

