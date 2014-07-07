firepick-delta-console
======================

LCD console for FirePick Delta.

Quick Information
===================
The firepick-delta-console is a display which is used to give the user useful information about their FirePICK delta machine.

##Features
*	IP Address Status
*	Time/date information

##To-Do
*	Interface with FireREST software to display job completeness status bar
*	Display other useful system info
*	Add buttons to allow the user to scroll through informational the different screens.


Instillation
===================
##Requirements
python-pip (for python 2.7)
python 2.7
python-setuptools
pip package rpi.gpio


##Automatic/Scripted Instillation
The install.sh script was written for a debian-based system, specifically the Raspberry Pi Rev. B running Raspberrian/FireREST. If you are using different software, please fork the repo and revise the script :).

* run the bash installer script install.sh.

##Manual Instillation
* Install the following dependancies manually:
		--* Python 2.7
		--* Python Setup Tools
		--* rpi.gpio python package

* Optional Dependancies:
		--* Pip for Python 2.7 (for installing the rpi.gpio package)
