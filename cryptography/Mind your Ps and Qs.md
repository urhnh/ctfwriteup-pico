# Challenge

> In RSA, a small e value can be problematic, but what about N? Can you decrypt this? values

Hint: Bits are expensive, I used only a little bit over 100 to save money

# Solution

```
Decrypt my super sick RSA:
c: 62324783949134119159408816513334912534343517300880137691662780895409992760262021
n: 1280678415822214057864524798453297819181910621573945477544758171055968245116423923
e: 65537
```

```n=p*q```

using factordb we obtain;

```p= 1899107986527483535344517113948531328331
q= 674357869540600933870145899564746495319033```

z= (p-1)(q-1)
d=  e-1mod(p-1)(q-1)
