# This is the python-tdd repo readme file.
Steps required to enable full-screen graphics on Ubuntu host are:
sudo apt-get install virtualbox-guest-dkms virtualbox-guest-utils virtualbox-guest-x11
sudo apt-get install dkms
sudo apt-get install build-essential module-assistant
sudo m-a prepare
In the Guest system, go to the top menu, and click Devices->Insert Guest Additions CD Image. This should mount the CD image.
Run the installation.

Reference: http://askubuntu.com/questions/451805/screen-resolution-problem-with-ubuntu-14-04-and-virtualbox
