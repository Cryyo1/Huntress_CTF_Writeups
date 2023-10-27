# Challenge 

Well would you listen to those notes, that must be some long phone number or something!


# Solution

- first u need to decode the .wav file using dtmf decode online or u can  use [this](https://github.com/ribt/dtmf-decoder)

```bash
└─$ dtmf dialtone.wav 
13040004482820197714705083053746380382743933853520408575731743622366387462228661894777288573

```

- after that use python to decode it from long to byte

```python
from Crypto.Util.number import long_to_bytes 
data=13040004482820197714705083053746380382743933853520408575731743622366387462228661894777288573
flag=long_to_bytes(data)
print(flag)
# Flag:
# b'flag{6c733ef09bc4f2a4313ff63087e25d67}'
```