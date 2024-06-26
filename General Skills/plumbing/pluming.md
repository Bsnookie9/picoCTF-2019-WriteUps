# Overview
- Tags: `Easy` `General Skills` `picoCTF 2019` 

# Description
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.

# Hints
- Remember the flag format is picoCTF{XXXX}
- What's a pipe? No not that kind of pipe... This [kind](http://www.linfo.org/pipes.html)

# Solution
We need to use the netcat command to connect to the host connection.  

However, we will need to pipe to a grep command (as the hint mentions) to search for the flag using the following command:   
`nc jupiter.challenges.picoctf.org 4427 | grep picoCTF`

![image](https://github.com/Bsnookie9/picoCTF-2019-WriteUps/assets/106827110/a632b0af-b2a7-4aa4-b8c3-6b0aea13a6b3)

Flag: `picoCTF{digital_plumb3r_5ea1fbd7}`
