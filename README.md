# LibreElecNetflix
# Automate the build of Netflix on LibreElec
I've re-built my RPi3 many times trying to get Netflix working. This is my attempt to automate my steps.

to start:
wget https://raw.githubusercontent.com/Callan05/LibreElecNetflix/master/step1.sh

sh ./step1.sh



ideas:
A single file to call from a CLI of a Linux/macOS terminal, asking for the IP of the Libreelec host and the new root password
* Ask for inputs
* connect to host, run step1
* wait for reboot
* connect to host, run step2
