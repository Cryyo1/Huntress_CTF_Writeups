# Challenge

Maybe you already know about base64, but what if we took it up a notch?

# Solution

- first i translated the chinese text into english but it doesn't seem to lead anywhere

```text
The bulbuls and the bulldozers are not the only ones who have to make a lot of money, but they are also the ones who have to make a lot of money, and they have to make a lot of money, and they have to make a lot of money. Hedges are used in the production of woodworking machines, and the production of steel pipes and other equipment is a common practice. The production of steel pipes and other equipment is a common practice. 㸍㸍ꍦ鱡汻欱 驣洸驣渰汢饣蝛蝛蝛蝛蝛蝛蝛蝛蝛蝛蝛蝛箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏箏
```

- started to search about similiar encoding technique and i found it :)) : base65536 [Read more here](https://github.com/qntm/base65536)

```bash

└─$ python
Python 3.11.5 (main, Aug 29 2023, 15:31:31) [GCC 13.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> from  base65536 import decode
>>> enc_text=open("baseffff1","r").read();
>>> print(decode(enc_text))
'Nice work! We might have played with too many bases here... 0xFFFF is 65535, 65535+1 is 65536! Well anyway, here is your flag:
flag{716abce880f09b7cdc7938eddf273648}'
>>> 

```