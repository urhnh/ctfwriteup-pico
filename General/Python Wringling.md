# Challenge

Python scripts are invoked kind of like programs in the Terminal... Can you run [this Python script](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py) using this [password](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/pw.txt) to get [the flag](https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en)?

Hint: Get the Python script accessible in your shell by entering the following command in the Terminal prompt: ```$ wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py```

Hint: ```$ man python```

# Solution

- open webshell

- ```wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/ende.py```

- ```wget https://mercury.picoctf.net/static/8e33ede04d02f3765b8c6a6e24d72733/flag.txt.en```

- ```python ende.py -d flag.txt.en```

- enter the password
