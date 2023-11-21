# Challenge

Can you look at the data in this binary: static? This BASH script might help!

# Solution

- open webshell

- ```wget https://mercury.picoctf.net/static/bc72945175d643626d6ea9a689672dbd/static```

- ```wget https://mercury.picoctf.net/static/bc72945175d643626d6ea9a689672dbd/ltdis.sh```

- ```chmod -x static``` (to make static executeable)

- ```./static``` (it will says Oh hai! Wait what? A flag? Yes, it's around here somewhere!)

-  I tried the same steps from previous challenge ```chmod -x ltdis.sh```

- ```./ltdis.sh static```

- ```cat static.ltdis.strings.txt``` (to view content of the file)

- Aha! flag is somewhere here
