[![GitHub license](https://img.shields.io/github/license/JoelShine/Jarvis-v2.0?style=flat-square)](https://github.com/JoelShine/Jarvis-v2.0/blob/main/LICENSE)[![GitHub stars](https://img.shields.io/github/stars/JoelShine/Jarvis-v2.0?style=flat-square)](https://github.com/JoelShine/Jarvis-v2.0/stargazers)

Jarvis-v2.0
===========

This is a major update of my project JARVIS-The-Ultimate-Project. You can check out my first project here [JARVIS-The-Ultimate-Project](https://github.com/JoelShine/JARVIS-The-Ultimate-Project). Made many changes and this is better than the previous version. Also included Speech Recognition and a very own **Launchpad** like Apples's Launchpad in Mac.

You can also see the the official website of Jarvis v2.0 [here](https://joelshine.github.io/Jarvis-v2.0/).

<p align="center">
  <img width="600" height="350" src="https://github.com/JoelShine/Jarvis-v2.0/blob/main/images/Jarvis.gif">
</p>

## About this project

This project is an example of a virtual assistant like **Siri**, **Cortana**, **Google Assistant** etc. A virtual assistant helps us to control the computer more efficiently and faster. It will be a great experience using Jarvis-v2.0 as it includes a great deal of modules to control the computer. Note that there is both a male voice version and female voice version for jarvis.

## Highlights of the project

Some of the project details are given below : 

1 ) Demo of Jarvis's very own Multimedia player (works perfectly) - In this [link](https://screenrec.com/share/3BD1q5AT9R), you can see the demo. Please note that you cannot play **".mp4"** videos in this player if you don't have this application called K-Lite Codec Pack Basic. Version
is not necessarily be the same, but you have to download it. It only works with .avi or .mp4 if you don't download K-Lite Codec Pack Basic.
This is the link to the download - https://files3.codecguide.com/K-Lite_Codec_Pack_1590_Basic.exe

**Screenshot of Jarvis's very own Multimedia Player**

[<img src="https://github.com/JoelShine/Jarvis-v2.0/blob/main/images/Multimedia Player official.png">](https://screenrec.com/share/3BD1q5AT9R)


-----------------------------------------------------------------------------------------------------------------------------------------
    
2 ) Demo of Jarvis very own Launchpad (works perfectly) - In this [link](https://screenrec.com/share/rJuHMs4UXQ), you can see the demo. It is a wonderful combination of PyQt5 and many other modules to create this. Hope you enjoy it.

**Screenshot of Jarvis's very own Launchpad**

[<img src="https://github.com/JoelShine/Jarvis-v2.0/blob/main/images/Jarvis Launchpad.png">](https://screenrec.com/share/rJuHMs4UXQ)


-----------------------------------------------------------------------------------------------------------------------------------------

## To improve this project

You can join in my discussions in github itself so that you can give suggestions regarding this project to make it wonderful even more. At the time being, this project can only be run in console and don't have a GUI. So you can talk about adding a GUI (Graphical User Interface) to this project so that it will be even more elegent looking, just like Tony Stark's. Feel free to comment and start any issues you face.

Link to my Github discussions - [Jarvis v2.0 Discussions](https://github.com/JoelShine/Jarvis-v2.0/discussions/1)

## Features of the modules used in this project

This project has a variety of features which can help you run the computer more efficiently. Please click on the **link** with the name of the module to set up the modules in your computer.

- [speech recognition](#speech-recognition) module for controlling the assistant using voice.
- [opencv-python](#opencv-python) module to capture images from webcam.
- [ctypes](#ctypes) module for controlling the system tasks like locking, restarting, shutdowning etc.
- [subprocess and operator](#subprocessandoperator) module like ctypes are also used for controlling the computer.
- [psutil](#psutil) module for *extracting* system information like remaining battery, etc.
- [plyer](#plyer) module for giving custom notifications to the computer.
- [pillow (but forked as PIL)](#PIL) module for showing images using the pillow module.
- [pytesseract](#pytesseract) module for extracting text from images.
- [youtube_dl](#youtube-dl) module for downloading youtube videosfrom web.
- [googlesearch](#googlesearch) module for searching on google with a query given as input from python.
- [time](#time) module for pausing the program accordingly.
- [tkinter](#tkinter) module for making GUI's like calculator, calendar etc. 
- [random](#random) module for choosing random things from a list.
- [datetime](#datetime) module for getting the current date and time.
- [wikipedia](#wikipedia) module for searching an input in wikipedia and printing the results.
- [webbrowser](#webbrowser) module for opening websites using python with a given url.
- [os](#os) module for opening and starting system files, folders and executable file also.
- [pyttsx3](#pyttsx3) module for text to speech using Sapi 5 (applicable to **Windows** only) For apple, there is [mac-say](https://pypi.org/project/mac-say/) module.
- [winshell](#winshell) module in our project, is used to empty the recycle bin and it is applicable to **Windows** only.
- [pyjokes](#pyjokes) module is used to give random jokes.
- [feedparser](#feedparser) module is to parse or extract information from a website.
- [shutil](#shutil) module offers a number of high-level operations on files and collections of files.
- [requests, urllib.requests and bs4(BeautifulSoup)](#requests) modules are used for web scraping like extracting information from a website.
- [pygame (pygame.mixer)](#pygame) module is used for controlling the audio played in the computer using tkinter and pygame.
- [pyqrcode](#pyqrcode) module to generate qr codes to open websites.
- [math](#math) module to do mathematical calculations.
- [keyboard](#keyboard) module to send keys from keyboard automatically like press enter key and other keys.

## Commands used in this program to operate Jarvis (For jarvia-fmale version, just replace jarvis with jarvia)

- **To say hello to jarvis -** "*hello jarvis*" , "*hey jarvis*" , "*hi jarvis*"
- **To greet jarvis -** "*good morning jarvis*" , "*good evening jarvis*" , "*good night jarvis*"
- **To ask jarvis how he is -** "*how are you jarvis*" , "*how do you do jarvis*"
- **To ask jarvis about himself -** "*what is your name*" , "*who are you*"
- **To ask jarvis to wait -** "*wait jarvis*" , "*wait please*"
- **To ask jarvis to open apps, sites and programs**
  - "*open cmd*" , "*open command prompt*"
  - "*open google*" , "*show google*"
  - "*open calendar*" , "*show calendar*"
  - "*open whatsapp*" , "*show whatsapp*" (If you have whatsapp)
  - "*open wolframalpha*" , "*show wolframalpha*"
  - "*open youtube*" , "*show youtube*"
  - "*open gmail*" , "*show gmail*" , "open g mail" , "show g mail"
  - "*open notepad*" , "*show notepad*"
- **Ask jarvis about the time -** "*what is the time jarvis*" , "*say the time jarvis*"
- **Ask jarvis about the current weather -** "*what is the weather jarvis*" , "*get the weather jarvis*"
- **Ask jarvis about the date -** "*what is the date jarvis*" , "*say the date jarvis*"
- **Ask jarvis about the time -** "*what is the time jarvis*" , "*say the date jarvis*"
- **Ask jarvis about the current news -** "*what is the news jarvis*" , "*say news jarvis*" , "*open news jarvis*"
- **Ask jarvis to say some joke -** "*say a joke jarvis*" , "*tell a joke jarvis*"
- **Ask jarvis to play some music -** "*play a music jarvis*" , "*play some music jarvis*"
- **Ask jarvis to take a picture -** "*take a pic jarvis*" , "*take a picture jarvis*"
- **Ask jarvis to take screenshot -** "*take a screenshot jarvis*"
- **Ask jarvis to take a note -** "*take a note jarvis*" , "*take some note jarvis*"
- **Ask jarvis to lock the device -** "*lock the device jarvis*"
- **Ask jarvis to sent a gmail -** "*sent a gmail jarvis*" , "*sent mail jarvis*"
- **Ask jarvis to empty the recycle bin -** "*empty recycle bin jarvis*" , "*empty trash jarvis*" , "*empty bin jarvis*"
- **To stimulate jarvis -** "*wake up jarvis*" , "*jarvis*"
- **To search in wikipedia -** "*search in wiki jarvis*" , "*search wikipedia jarvis*"
- **To open jarvis's own recorder -** "*record jarvis*" , "*jarvis record*"
- **To download youtube videos -** "*download a video jarvis*" , "*download youtube video jarvis*"
- **To extract text from image (pytesserct) -** "*ocr jarvis*" , "*extract text from image jarvis*"
- **To generate qr code to open website -** "*qr code jarvis*" , "*q r code jarvis*"
- **To show the remaining battery -** "*what is the battery remaining*" , "*show battery jarvis*"
- **To open jarvis's own video player -** "*record jarvis*" , "*jarvis record*"
- **To open jarvis's own launchpad -** "*record jarvis*" , "*jarvis record*"
- **To open jarvis's own browser -** "*open my browser jarvis*" , "*open browser jarvis*"
- **To tarnslate -** "*tarnslate jarvis*"
- **To search something on google -** Just say what you want to search on google.

## Major defects of the project

Some parts of this project is made into executables, so it contains many **".dll"** files and it may run only in Windows system. If you want the real python script, please contact me in my [Jarvis v2.0 Discussions](https://github.com/JoelShine/Jarvis-v2.0/discussions/1). Another defect is if you have any Antivirus running while downloading or using the program, it may take it as a malware and delete it. So, during the running of this program, No Antivirus should be running in the background.

## Support
Your support encourages me to make more projects and benefit others. Support me on youtube. Subscribe to my channel.
<br />
<hr />
[<img height="30" src = "https://img.shields.io/badge/Youtube-%23E4405F.svg?&style=for-the-badge&logo=Youtube&logoColor=white">](https://www.youtube.com/channel/UCKaqF5TBF2j_R8PB7Sfu_mg/featured/view_as=subscriber)
