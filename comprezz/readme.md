# Challenge 

Someone stole my S's and replaced them with Z's! Have you ever seen this kind of file before?

# Solution 

- check file type first we can see that its 16b compress file
```bash
└─$ file comprezz 
comprezz: compress'd data 16 bits
```

-  uncompress the file using 'uncompress' and cat the result u wil get the flag (dont forget to add extention .z)

```bash
└─$ uncompress comprezz.z

└─$ ls
comprezz

└─$ file comprezz 
comprezz: ASCII text

└─$ cat comprezz 
flag{196a71490b7b55c42bf443274f9ff42b}
```

