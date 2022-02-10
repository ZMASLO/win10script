# Ultimate Windows Toolbox
This script is the culmination of many scripts and gists from github based on work Chris Titus. I've added my own functions for easier reading and adding new functions. I'm using this script to setup my benchmark enviroment

## My Additions
- functions to reduce code lenght
- installing local exe
- copying files to desktop

## How to Run
Paste this command into Powershell (admin):
```
iex ((New-Object System.Net.WebClient).DownloadString('https://bit.ly/3HKUriB'))
```
Or, shorter:
```
iwr -useb https://bit.ly/3HKUriB | iex
```

For complete details check out https://christitus.com/debloat-windows-10-2020/
