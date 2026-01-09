# Rset
## **Never** lose a prized vehicle to a server restart again. 
 This lightweight utility tracks server restart times with high precision,<br>  enabling you to secure your gear before the restart, <br>  and ensuring you are the first one in the queue.
<br><br>**Designed in-time with, and for, the _Escape from Dayz_ by Goon DayZ server.**
## **Preview**
<img width="720" height="186" alt="0 1 002" src="https://github.com/user-attachments/assets/7059c73f-138c-49c4-86f6-0f18b03370bd" /><br>
With the release binaries you can begin utilizing the utility almost immediately. No assembly needed.

## **How to use**
* Simply download the binary from the releases and run it anywhere to start the application. 
* Make sure DayZ is in windowed mode if you want the app to overlay.
* In the settings page ([+] button), you can toggle notification beeps, and the classic mode for the progress bar in the theme of the [alpha](https://imgur.com/a/WwhVPsn) version of the utility.
<br><br><br><br><br>
# **Nerd stuff**
<br><br>
## **Building from source**
Install Python version 3.11<br><br>
Install the requirements with<br>
```py/python -m pip install pyinstaller```<br><br>
Make sure to install requirements to the correct version if you have multiple python versions.<br> > ```py/python -3.11 -m pip install pyinstaller```<br><br>
Alternatively install the requirements from the requirements file.<br>
```py/python -3.11 -m pip install -r requirements.txt```<br><br>
Compile using PyInstaller,<br>
> (Replace "PATH_TO" with the corresponding path, and enter only 'py' or 'python', not 'py/python')<br><br>
> eg. ```py/python -3.11 C:\PATH_TO\Python\Python311\Lib\site-packages\PyInstaller\__main__.py  --noconsole --onefile --collect-all imgui --add-binary "C:\PATH_TO\Python\Python311\Lib\site-packages\glfw\glfw3.dll;." C:\PATH_TO\Rset.py```
<br><br>
## **Release Binary Virus Total + Analysis**
[Detect It Easy](https://github.com/horsicq/Detect-It-Easy)
<img width="1700" height="618" alt="die" src="https://github.com/user-attachments/assets/0d8b5a7d-12e6-4bd9-b761-b26c3d1588a6" />
[Virus total](https://www.virustotal.com/gui/file/4727c9ae7ea3d0aa0cb0616780f9e8c97da59d0f18c7ae9bdd7efaf42699e599)<br>
<img width="789" height="1265" alt="vt" src="https://github.com/user-attachments/assets/2ec7ae98-2207-4b0c-bd25-50bd564e36cf" />
