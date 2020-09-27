# JARVIS AI Assistent
-----------------------
A virtual computer based assistant, perform various task & instructions.

Table of Content
----------------
* Demo

* Overview

* Motivation

* Installation

* Steps

* Future scope of project


DEMO
------
![2020-09-28 (23)](https://user-images.githubusercontent.com/41515202/94376867-ea907a00-013a-11eb-8c59-998f27f4496b.png)

![2020-09-28 (24)](https://user-images.githubusercontent.com/41515202/94376869-ebc1a700-013a-11eb-95b6-086cf0e2e2dd.png)

![2020-09-28 (25)](https://user-images.githubusercontent.com/41515202/94376870-ecf2d400-013a-11eb-95a5-fe3592f01682.png)

![2020-09-28 (26)](https://user-images.githubusercontent.com/41515202/94376871-ee240100-013a-11eb-9884-45ec55bd5263.png)


Overview / What is it ??
------------------------
* A simple personal voice activated desktop assistant in python for Windows which works on the command line. 

* He can talk to you if you enable his voice. He can tell you the weather, he can find restaurants and other places near you. He can do some great stuff for you.

* Imagine how easier it would be to send emails without typing a single word, doing Wikipedia searches without opening web browsers, and performing many other daily tasks like playing music with the help of a single voice command

Motivation / Why / Reason ??
-------------------------------
* The sole purpose of A.I is to develop machines that can perform human tasks with the same effectiveness or even more effectively than humans.
* It is a fact that our virtual assistant is not a very good example of A.I., but it is an A.I.

Installation / Tech Used
--------------------------
* Audio – pyttsx3 – python library which will help us to convert text to speech. In short, it is a text-to-speech library. It works offline, and it is compatible with Python 2 as well the Python 3.

* Sapi5 - Speech API developed by Microsoft. Helps in synthesis and recognition of voice

* VoiceId - Voice id helps us to select different voices.
    voice[0].id = Male voice 
    voice[1].id = Female voice

STEPS/PROCESS
----------------
* Audio – pyttsx3 – python library which will help us to convert text to speech. In short, it is a text-to-speech library. It works offline, and it is compatible with Python 2 as well the Python 3.

* Sapi5 - Speech API developed by Microsoft. Helps in synthesis and recognition of voice

* VoiceId - Voice id helps us to select different voices.
    voice[0].id = Male voice 
    voice[1].id = Female voice
* Main() fn - we will call our speak function.

* Speak Function : 
This Function will take audio as argument to speak/pronounce something.
Convert our text to speech. 
Whatever you will write inside this speak() function will be converted into speech
Assistant own voice, and it is ready to speak.

* Wishme Function : 
This Function will make your Jarvis wish you according to system time.
Take command Function This Function will allow your Jarvis to take microphone input from the user and returns a string output
Wish or greet the user according to the time of computer or pc
Need to import a module called datetime
We have stored the integer value of the current hour or time into a variable named hour. Now, we will use this hour value inside an if-else loop

* Command Function : 
Before need to install a module called speechRecognition
Should be able to take command with the help of the microphone of the user's system
Make a takeCommand() function, with the help of the takeCommand() function, our A.I. assistant will be able to return a string output by taking microphone input from the user

* Coding logic of Jarvis : 
We will develop logics for different commands such as Wikipedia searches, playing music, etc

* Task 1: To search something on Wikipedia : 
Need to install and import the Wikipedia module into our program
Use an if statement to check whether Wikipedia is in the search query of the user or not
If found in the user's search query, then two sentences from the summary of the Wikipedia page will be converted to speech with the help of speak function

* Task 2: To open YouTube site in browser:  
Import a module called web-browser
Use the elif loop to check whether the YouTube is in the query of the user or not
Open YouTube will be in the user's query, and the elif condition will be true

* Task 3 : To open Google site in browser : import a module called webbrowser
Use the elif loop to check whether the Google Search is in the query of the user or not
Open Google Search will be in the user's query, and the elif condition will be true

* Task 4 : To play music : 
Import a module called os
We first opened our music directory and then listed all the songs present in the directory with the help of the os module
With the help of os.starfile, you can play any song of your choice
I am playing the first song in the directory

* Task 5 : To know current time : 
Using DateTime() fn & storing the current or live of the system into a variable called strTime
After storing the time in strTime, we are passing this variable as an argument in speak function
Now, the time string will be converted into the speech.

* Task 6 : capable of opening your VS code editor or IDE with a single voice command : 
Need the code path of the application
Steps to get the code path of the application:
Step 1: Open the file location.
Step 2: Right-click on the application and click on properties.
Step 3: Copy the target from the target section
After copying the target of the application, save the target into a variable. Here, I am saving the target into a variable called codePath, and then we are using the os module to open the application.


Future scope of project
-----------------------
Use multiple Algorithms.

Optimize to do more work

make more effective
