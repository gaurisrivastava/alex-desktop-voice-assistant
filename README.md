# Alex-Desktop-Voice-Aassistant
Alex is a desktop voice assistant which is an application program that understands natural language voice commands and completes tasks for the user.

### FEATURES:

- It can send emails for you.

- It can play music for you.

- It can do Wikipedia searches for you.

- It is capable of opening websites like Google, Youtube, etc., in a web browser.

- It is capable of opening your code editor or IDE with a single voice command.

###   Let's start building our own A.L.E.X

Starting with pycharm using python
I am going to use the Pycharm IDE.  Start a new project and make a file called alex.py.

### Defining Speak Function

We will make a function called speak(). This function will take audio as an argument, and then, it will pronounce it.

### What is pyttsx3?
A python library which will help us to convert text to speech. In short, it is a text-to-speech library.
It works offline, and it is compatible with Python 2 as well the Python 3.

###### Installation:
"
pip install pyttsx3
"
### What is sapi5?
Speech API developed by Microsoft.
Helps in synthesis and recognition of voice.

### What Is VoiceId?
Voice id helps us to select different voices.
voice[0].id = Male voice 

voice[1].id = Female voice

### Defining Wish me Function :
Now, we are going to make a wishme() function, that will make our A.L.E.X wish or greet the user according to the time of computer or pc. To provide current or live time ,we need to import a module called datetime. I
 
### Defining Take command Function :
With the help of the takeCommand() function,will be able to return a string output by taking microphone input from the user.

#### Coding logic of Alex
It will develop logics for different commands such as Wikipedia searches, playing music, etc.

### What is smtplib?
Simple Mail Transfer Protocol (SMTP) is a protocol that allows us to send emails and to route emails between mail servers. An instance method called sendmail is present in the SMTP module. This instance method allows us to send an email.  It takes 3 parameters:
The sender: Email address of the sender.
The receiver:T Email of the receiver.
The message: A string message which needs to be sent to one or more than one recipient.
     
The E.N.D.

