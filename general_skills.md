
## strings

Can you find the flag in this file without actually running it? 
You can also find the file in /problems/strings_1_c7bac958dd6a4b695dc72446d8014f59 on the shell server. 

```
$ strings ~/Downloads/strings | grep -rnwi picoCTF
(standard input):2071:picoCTF{sTrIngS_sAVeS_Time_d7c8de6c}
```

## pipe

During your adventure, you will likely encounter a situation where you need to process data that you receive over the network rather than through a file. 
Can you find a way to save the output from this program and search for the flag? Connect with 2018shell.picoctf.com 2015. 

```
$ nc 2018shell.picoctf.com 2015 | grep picoCTF
picoCTF{almost_like_mario_8861411c}
```

