# Challenge

Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/5ef2e9103d55972d975437f68175b9ab/dolls.jpg)

Hint: Wait, you can hide files inside files? But how do you find them?

Hint: Make sure to submit the flag as picoCTF{XXXXX}

# Solution

```
wget https://mercury.picoctf.net/static/5ef2e9103d55972d975437f68175b9ab/dolls.jpg

unzip dolls.jpg

cd base_images

unzip 2_c.jpg

cd base_images

unzip 3_c.jpg

cd base_images
```


there's the flag hiding! we can now stop unzipping and try to open the file


```
cat flag.txt
```

   
