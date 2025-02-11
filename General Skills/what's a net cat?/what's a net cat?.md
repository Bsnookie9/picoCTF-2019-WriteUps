# Overview
- Tags: `picoCTF2019` `General Skills`
- `100 points`

# Description
Using netcat (nc) is going to be pretty important. Can you connect to `jupiter.challenges.picoctf.org` at port `64287` to get the flag?

# Hints
nc [tutorial](https://linux.die.net/man/1/nc)

# Solution
Simply talk to the host over the port number and echo the message to the command line.

`echo | nc jupiter.challenges.picoctf.org 64287`

<kbd>![Screenshot](https://github.com/user-attachments/assets/9fae4ec1-3cfa-4e65-8f1e-73551f55bbd7)</kbd>

# Flag
`picoCTF{nEtCat_Mast3ry_284be8f7}`
