# CameraPhishing

What is CamPhish?

CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device.

These are the following steps you have to go through to breach in someone's device by sending them a malicious link and get access to there webcam:

STEP 1: clone this repository using following command ( in Kali Linux):
	git clone https://github.com/techchipnet/CamPhish
	cd CamPhish
	bash camphish.sh or ./camphish.sh


STEP 2: choose tunnel server
	Ngrok
	Serveo.net
 
STEP 3: choose a template
	here I chose Live Youtube TV

STEP 4: enter youtube watch Id

STEP 5: enter ngrok authtoken

STEP 6: you'll get the link, send it to your target

STEP 7: when the target will open the link you'll get the target's IP address along with their phone or desktop's cam shots.


<NOTE: THIS IS ONLY FOR EDUCATIONAL PURPOSE DON'T USE THIS WITHOUT PERMISSION.>
