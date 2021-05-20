# CSAmeetAutomation
Bot for joining online classes at the right time (This bot is optimized for S4 CSA students -  JECC).

## Refer this video for a more detailed explanation of using this bot.
[YouTube Video - Click Here](https://youtu.be/mx6fBHsQoXk)

# Usage 
The bot asks you for a ```AuthUser count``` while running. The required AuthUser count is the the position of logged in jecc mail id.The first id is 0 the second one is 1 and so on. For Eg:


![AuthUser Demo Image](https://user-images.githubusercontent.com/66511659/118859741-337a8600-b8f8-11eb-88e6-e44b50b3b628.jpeg)

Here my required AuthUser count is 1 as my JECC mail id is logged in as the second account.

> The bot uses keyboard hot keys to turn off the cam and mic and also to join class.So kindly avoid engaging with the meet window while joining a class is in progress.


# Installation

## Windows 

Download the [meetautomation.exe](https://github.com/TheAmalShibu/CSAmeetAutomation/releases/download/v1.0/meetautomation.exe) from the releases and run/execute the file.

## Linux or Compiling Python Code

Download the [CsaMeetBot.zip](https://github.com/TheAmalShibu/CSAmeetAutomation/releases/download/v1.0/CsaMeetBot.zip) file from the releases and extract it's contents.
The script depends or certain packages. You can install them by
```
pip3 install pyautogui
pip3 install datetime
```
or
```
pip3 install -r requirements.txt
```
After installing the dependencies you can run the script by
```
python3 meetautomation.py
```
> Python3 is preffered over other versions of python.

> For the current meet bot version chromium based browers (Google,Brave) are preffered over other browsers.

Do raise an issue for feature request or bug fixes :)
