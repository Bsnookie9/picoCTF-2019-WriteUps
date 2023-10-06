# Overview
- Tags: `picoCTF 2019` `General Skills`
- `200 points`

# Description
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary.   
Can you get the flag from this program to prove you are on the way to becoming 1337?   
Connect with `nc jupiter.challenges.picoctf.org 29956`.

# Hints
- I hear python can convert things.
- It might help to have multiple windows open.

# Solution
This challenge is easy, but you must work quickly. Instead of writing a Python script, as the hint mentions, just manually do the work.  
Go to CyberChef and add these three recipes: `From Binary`, `From Octal`, and `From Hex`. 

![based](https://github.com/Bsnookie9/picoCTF-2019-WriteUps/assets/106827110/7b2f715b-7ca5-44fc-b5c5-d852f2447c30)

Copy and paste the netcat command and hit enter. You’ll be prompted with the first question. Copy and paste the binary text into CyberChef. Do the same for the octal string and the hex string. Answer the questions correctly and you'll get the flag. 

![based(2)](https://github.com/Bsnookie9/picoCTF-2019-WriteUps/assets/106827110/5dede82e-ee82-45f7-9bfa-acc3406da826)

Flag: `picoCTF{learning_about_converting_values_b375bb16}`
