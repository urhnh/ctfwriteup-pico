# Challenge

I wonder what this really is... [enc](https://mercury.picoctf.net/static/2b4cea9b07db22bf4f933fddd1b8caa9/enc) ```''.join([chr((ord(flag[i]) << 8) + ord(flag[i + 1])) for i in range(0, len(flag), 2)])```

Hint: You may find some decoders online

# Solution

- downloading enc will give flag: ```灩捯䍔䙻ㄶ形楴獟楮獴㌴摟潦弸弰㑣〷㘰摽```

- i have seen the hard way to solve this but since it is just 20 points, lets do the easy way (actually the hard way is T_T for me huhu)

- put into cyberchef and use the magic recipe (please scroll, very clumsy of me not to notice the flag is there yes!)

