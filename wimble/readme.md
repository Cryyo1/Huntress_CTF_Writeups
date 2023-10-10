# Challenge
Author: @JohnHammond

"Gretchen, stop trying to make fetch happen! It's not going to happen!" - Regina George, Mean Girls

Download the files below.

# Solution

- I started by extracting files from the 7z file

- after that i got fetch file after small search it wim file which can be extracted 

```bash
└─$ file fetch
fetch: Windows imaging (WIM) image v1.13, XPRESS compressed, reparse point fixup
```

- after some more searching i found a tool to extract information from extracted files "from the wimfile" [here](https://ericzimmerman.github.io/#!index.md)

- there is another fetch folder inside the fetch folder that need to be extracted "fetch.zip"

- after that i used the PEcmd tool to extract informations and looked for the flag inside the output file

```bash
PECmd.exe -d "fetch~\fetch" >> out.txt 
```

```txt
_NONE_CE876B9E12F802EA\GDIPLUS.DLL
59: \VOLUME{01d89fa75d2a9f57-245d3454}\WINDOWS\SYSTEM32\TZRES.DLL
60: \VOLUME{01d89fa75d2a9f57-245d3454}\WINDOWS\SYSTEM32\EN-US\TZRES.DLL.MUI
61: \VOLUME{01d89fa75d2a9f57-245d3454}\USERS\LOCAL_ADMIN\DESKTOP\FLAG{97F33C9783C21DF85D79D613B0B258BD}
62: \VOLUME{01d89fa75d2a9f57-245d3454}\WINDOWS\SYSTEM32\MSCTF.DLL
```
