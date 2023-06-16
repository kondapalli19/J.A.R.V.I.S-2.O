# Voice2Text+: Your AI Companion for Voice-Powered Efficiency
This project uses NLP to communicate using the OpenAI API key and also relies on an internet connection for better accuracy of results. Additionally, it provides real-time news, weather reports, and the current time.

📃Table of Contents
-------------------

* Introduction
* Features
* Installation
* Troubleshooting
* References


🤗Introduction
--------------------

Project, "Voice2Text+: Your AI Companion for Voice-Powered Efficiency," is an innovative voice-enabled personal assistant that integrates natural language processing (NLP) technology. This intelligent assistant allows users to interact using voice commands and provides outputs in both text and voice formats. With the ability to access the internet, play games, check weather updates, and read news, Voice2Text+ revolutionizes the way users communicate and engage with their digital environment. Experience enhanced productivity and convenience as Voice2Text+ translates your voice into actionable information, making tasks simpler and more efficient.


🚀Features
--------------------

- Communicate with user in Natural language processing (NLP) and act as an intelligent agent by giving answers to your questions.

- Opens Google, Youtube, vs code on taking command by micrphone.

- Reads the wikipedia content.

- Telling the current time, checking the weather of the inputted city, read the headlines of the today's news and also provides the link.

- play music, play games.

- Tell the schedule (timetable) provided.

- stops after getting the shutdown command.


🧑‍💻Installation
----------------------

Software Requirements:

        * Python version : Python 3.10.8

        * vs code version : 1.74.0

        * table.txt : File provides the time table

        * Installing python modules : 

                pip install <module_name>

                module_name
                - pyttsx3
                - psutil
                - wikipedia
                - SpeechRecognition
                - requests
                - pywin32
                - bs4

        * Get API from newsapi.org to get the today's news daily.
       
        * GET OPEN AI API KEY: For using Natural language Processing.
              
        * In play music, music_dir variable give the path of the directory which contains only music file.


⚙️Troubleshooting
-----------------------

Check microphone of your system is properly working or not fix this issue settings > sound settings > choose your input device.
After that check if Google assistant is taking your voice as command or else fix this issue first.


💁References
----------------------


* If pip is not working properly.

        https://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command

        If that doesn't work :
                For Windows, when you install a package, you type:

                        python -m pip install [packagename]


* If speak function does not working properly.

        Check if it's imported or not.

                from win32com.client import Dispatch
                speak=Dispatch("SAPI.spVoice")
                speak.Speak(string)

                or

                from win32com.client import Dispatch

        
        



How to get API for free?
newsapi.org 



If SpeechRecognition is not working.
Check the microphone of your system is working or not if yes then check the module SpeechRecognition module.


If any other problem occured
contact me through email - kkoyal19599@gamil.com






 <b>GET OPEN AI API KEY</b>: For using Natural language Processing.<br/><br/>
 <b>GET NEWS API</b>: For the latest news everday.
 
