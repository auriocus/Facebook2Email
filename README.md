Facebook2Email
==============

This project allows you to convert Facebook messages into email format (mbox file) in order to archive them. mbox files can be imported into many email clients and are natively used e.g. by Thunderbird. 

Instructions
============
* Download your Facebook messages. See https://www.facebook.com/help/212802592074644 Select only messages, and download in JSON format.
* Unzip the resulting file in the root directory of this project. You should see a foolder structure starting with messages/
* Run Facebook2Email.py (not yet written, but see below)
* Import the mbox files into youtr email program. For Thunderbird, you can use the Import/Exporttools addon https://addons.thunderbird.net/de/thunderbird/addon/importexporttools-ng/ or simmply copy the mbox files into your profile directory (do this when you know what you are doing)

This project is in Alpha stage. Currently, a Jupyter notebook exists with some experiments, it converts a single thread into an mbox file
