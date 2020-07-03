# Pyautogui-Zipato
An Automation and Recorder Script for Zipato

**_Make sure you're running this script on laptop or computer with 1366 x 768 display resolution_**

## Installing prerequisite files
1. Download prerequisite files on this [link](https://bit.ly/pyautodep). Extract on root folder.
2. Install python 2.7 for windows, make sure python already added to windows path environment. Test using cmd type `python`
3. Install pip
   - `python get-pip.py`
   - Make  sure pip already added to windows path environment. Test using cmd type `pip`
4. Install dependencies
   - `pip install pyHook-1.5.1-cp27-cp27m-win_amd64.whl`
   - `pip install pywin32-227-cp27-cp27m-win_amd64.whl`
5. Install PyWin32, go inside the folder where Python is installed, run the following command `python Scripts\pywin32_postinstall.py -install`
6. Install pyautogui
   `pip install pyautogui`
   
## Start recording
1. Create a new directory on root folder with name **recorder**
2. To record activity type: `python record.py template_name` . For example: `python record.py BWS_MAIN`
3. Press esc button on your keyboard to end your recording.
_nb: use firefox for browser_
