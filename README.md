#!/bin/bash

# First Update and Upgrade
# Then AutoClean and AutoRemove
#Ending with a little welcome message

sudo apt update
echo *-*-*-*-*-*-*-*-*-*-*-*
sudo apt upgrade
echo *-*-*-*-*-*-*-*-*-*-*-*
sudo apt autoclean
echo *-*-*-*-*-*-*-*-*-*-*-*
sudo apt autoremove
echo   
echo   
echo   
echo Scrubby has checked for updates and put everything it its place.
echo Now Go Forth and Hack

# At a later time I want random responses on the echo output
