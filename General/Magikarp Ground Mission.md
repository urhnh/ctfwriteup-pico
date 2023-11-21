# Challenge

Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin. Login via `ssh` as `ctf-player` with the password, `6d448c9c`
Additional details will be available after launching your challenge instance.

Hint: Finding a cheatsheet for bash would be really helpful!

# Solution

- click launch instance and enter the given command ```ssh ctf-player@venus.picoctf.net -p 54731```

- login as ctf-player with the given password

- ```ls``` (to see file in the directory)

- ```cat 1of3.flag.txt``` (to view content of the file)

- instructions-to-2of3.txt says ```Next, go to the root of all things, more succinctly `/` ```

- ```cd /``` (change to / directory)

- ```ls``` (to see file in the directory)

- ```cat 2of3.flag.txt``` (to view content of the file)
  
- instructions-to-2of3.txt says ```Lastly, ctf-player, go home... more succinctly `~` ```

- ```cd ~``` (change to ~ directory)

- ```ls``` (to see file in the directory)

- ```cat cat 3of3.flag.txt``` (to view content of the file)
