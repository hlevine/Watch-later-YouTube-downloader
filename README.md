Watch-later-YouTube-downloader
==============================

This is a script I compiled from various resources on the internet to download my watch later Youtube Videos onto my server at home.  All I have to do to start the download is add the video to my watch later list.  Once downloaded the watch later item will be removed from the list.

Install
Unfortunalty only works with linux desktop as a browser is required to authenticate for the first time.

Requirements
1.  Python 2.7
2.  Youtube-dll
3.  python setup tools
3.  python-gflags
4.  google-api-python-client
5.  python httplib2 library

You will need a Google Developers console account.

First:
On the Google Developer console create a project called lets say Getem.   Enable the YouTube Data API v3.   Create a new client id with desktop access.   Download the file into a folder on the user home folder where you would like to save your video.  Save it as client_secrets.json. 

Second:
On your linux box save the client_secrets.json and the getem.py files in the same folder.
Verify that you have python 2.7 installed.
Install python setup tools and youtube-dll with apt or which ever package manager you have.
The python librarys can be install with easy_install.

The folder youtube_download folder will be created.

Once collected the dwatch later video will be removed from the list.

Acknowledgements:
Most of this list came from the blog of Olivier Corradi's. (http://oliviercorradi.wordpress.com/)

