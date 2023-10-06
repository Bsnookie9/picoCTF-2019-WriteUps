# Overview
- Tags: `picoCTF 2019` `General Skills`
- `100 points`

# Description
Can you find the flag in `file` without running it?

# Hints
`strings`

# Solution
Download the `strings` file. Instead of using strings to find the flag, use the grep command to find the plaintext of the flag using the expression `strings strings | grep picoCTF`

![strings](https://github.com/Bsnookie9/picoCTF-2019-WriteUps/assets/106827110/888bea92-2e01-49fa-b4d0-ded2caa7bc96)

Flag: `picoCTF{5tRIng5_1T_7f766a23}`
