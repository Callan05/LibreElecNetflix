# LibreElecNetflix
## Automate the build of Netflix on LibreElec

Basically, following these steps:
https://github.com/asciidisco/plugin.video.netflix/wiki/Installation

I've re-built my RPi3 many times trying to get Netflix working. This is my attempt to automate my steps.

to start:
wget https://raw.githubusercontent.com/Callan05/LibreElecNetflix/master/step1.sh

sh ./step1.sh



## ideas/to-do
* Change timezone
* Change Root Password
* Change hostname
* setup default credentials from secure store (or input on cli)
* setup default folder shares from secure store

### A single file to call from a CLI of a Linux/macOS terminal, asking for the IP of the Libreelec host and the new root password
* Ask for inputs
* connect to host, run step1
* wait for reboot
* connect to host, run step2
