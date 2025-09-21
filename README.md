# Serverless Digital Sign Age

This Project is a Digital Sign Age system entirely Serverless ( Proof of Concept )

This system use MQTT, Websockets and Airtable into a simple javascript pages made with the help of ChatGPT.



# PLAYER
- A HTML page with Javascript to show images or videos

![alt text](https://i.imgur.com/S1m31HJ.png)

# CONTROLLER
- A HTML page with Javascript to control the Remote Screen by Websockets

![alt text](https://i.imgur.com/4qPVPM6.png)

OBS: The controller is under constant development and improvement.

# ONLINE DATABASE
-A online smartsheet database to store images and videos

https://airtable.com/appJenx8y4mRZDo6e/shrqI3K6SwXNqCxrV

## How it works ( DEMO )

### Setup a SCREEN

1 - Open the PLAYER in a Browser URL https://etiquetasio.github.io/serverless-ds/  of a new SCREEN ( Can be Windows, Mac, Android, etc, just neet to be Chrome ... ), the Player will connect to a public MQTT Server ( hivemq ) and its communication is done by WS:\\ ( websockets ), after you open the controller will send messages to the DUID topic of screen and the browser session wil react to its commands.

2 - A QRCODE and a DUID will be automatically generated    ( If you wish, you can open the CONTROLLER by clicking the QRCODE element to get the link )

![alt text](https://i.imgur.com/uFyRbwX.png)

3 - Get your smartphone and capture QRCODE url with your Camera, now you can control the Screen Remotely

4 - For now you can send image URLs , images portrait or landscape...



# Todo list:

Add videos to Smartsheet and link to a SCREEN

Schedule the content (next release ) by Smartsheet Database

Rotate Screen better way 

Better resposive support

Elektron versions for Windows, Linux and MacOS

PWA version for Android

Remote fullscreen activation for Elektron releases and Android release





