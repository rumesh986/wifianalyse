#WIFIANALYSE

### About
wifianalyse is a simple bash script that allows you to get the signal level, link quality and ping time of your device connected to a network. This script was tested on a Raspberry Pi running raspbian and a laptop running Ubuntu 16.04. 

### Usage
Using the script is very simple. just open a terminal `cd` to the directoryu containing the script and run `./wifianalyse`. if you to run the script from anywhere place the script in `/usr/local/bin` folder. You will be asked to enter the inerface name and ip addresss of your router when you run the script. This information is vital to the running of the script so please enter the correct information. the interface name can be found by running `iwconfig`.