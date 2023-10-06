# Overview
- Tags: `picoCTF 2019` `General Skills`
- `100 points`

# Description
Can you find the flag in `file`? This would be really tedious to look through manually, something tells me there is a better way

# Hints
grep `tutorial`

# Solution
Download the file. Use the grep command to look for the specific expression "picoCTF": `strings strings | grep picoCTF`

![grep](https://github.com/Bsnookie9/picoCTF-2019-WriteUps/assets/106827110/7fdab4a7-b83e-402f-838b-64513d6a8e9b)

Flag: `picoCTF{grep_is_good_to_find_things_5af9d829}`
