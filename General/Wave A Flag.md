# Challenge

Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm) has extraordinarily helpful information...

Hint: This program will only work in the webshell or another Linux computer.

Hint: To get the file accessible in your shell, enter the following in the Terminal prompt: ```$ wget https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm```

Hint: Run this program by entering the following in the Terminal prompt: ```$ ./warm```, but you'll first have to make it executable with ```$ chmod +x warm```

Hint: ```-h``` and ```--help``` are the most common arguments to give to programs to get more information from them!

Hint: Not every program implements help features like ```-h``` and ```--help```.

# Solution

- open webshell

- ```wget https://mercury.picoctf.net/static/a14be2648c73e3cda5fc8490a2f476af/warm```

- ```chmod +x warm``` (to make file executable)

- ```./warm``` (to execute file)

- ```./warm -h``` (to pass -h)
