This script is a simple .vbs script that will allow you to install multiple fonts ont a windows computer.
This is useful to install a list of custom fonts on a pc.

Call script via CMD or in a Batch file using the following format as an example:
cscript "C:\Your Folder\YourInstallScript.vbs"


If you need to install more than one font at a time just copy and paste the last line of the script and add it to the bottom for each additional font you would like to install.

Example:
objFolder.CopyHere "C:\Scripts\Myfont.ttf"
objFolder.CopyHere "C:\Scripts\Myfont.ttf"
