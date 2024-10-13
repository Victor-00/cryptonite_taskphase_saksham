## Challenge 1
This challenge simply wanted me to read out the flag using the cat command so did 'cat flag' to get the flag.

The commands :- <br/>
`hacker@commands~cat-not-the-pet-but-the-command:~$ cat flag`<br/> 
`pwn.college{M54yhtA5oj6kVB927Et9uQmzQ5t.dFzN1QDLwIjN0czW}`<br/>

- - -

## Challenge 2
This challenge said it didnt copy the flag to home directory but rather i can read it by using the absolute path for flag with cat so i did 'cat /flag'.

The commands :- <br/>
`hacker@commands~catting-absolute-paths:~$ cat /flag`<br/> 
`pwn.college{k2GYO3AdGrWwS9ujAylMAryoa6X.dlTM5QDLwIjN0czW}`<br/>

- - -

### Challenge 3
Here we need to retrieve the __flag__ file from its absolute path.
```
You cannot use the 'cd' command in this level, and must retrieve the flag by 
absolute path. Plus, I hid the flag in a different directory! You can find it 
in the file /lib/lsb/init-functions.d/flag. Go cat it out **without** cding 
into that directory!
hacker@commands~more-catting-practice:~$ cat /lib/lsb/init-functions.d/flag 
pwn.college{Ede2fI9-Z0oABaBqW0gQG3HGdtW.dBjM5QDLwIjN0czW}
```

- - -

### Challenge 4: grepping for a needle in a haystack.
We learn about the `grep` command that searches for a string or lines of text in a challenge.
```
hacker@commands~grepping-for-a-needle-in-a-haystack:~$ grep pwn cat /challenge/data.txt 
grep: cat: No such file or directory
/challenge/data.txt:pwning
/challenge/data.txt:pwn.college{MnN8VU3fKaGSixQSukN7SBNqdu0.ddTM4QDLwIjN0czW}
/challenge/data.txt:pwn
/challenge/data.txt:pwned
/challenge/data.txt:pwns
```
- - -

### Challenge 5: listing files.
We learn about the `ls` command that lists all the files in the directory or path in argument.
```
hacker@commands~listing-files:~$ ls /challenge/
22506-renamed-run-30882  DESCRIPTION.md
hacker@commands~listing-files:~$ /challenge/22506-renamed-run-30882 
Yahaha, you found me! Here is your flag:
pwn.college{ollDEaEp2M9WTR_vXlKhmk0YMcm.dhjM4QDLwIjN0czW}
```
- - -

### Challenge 6: touch files.
We learn about the `touch` command that creates a blank new file in the directory or path in argument.
```
hacker@commands~touching-files:~$ touch /tmp/pwn /tmp/college
hacker@commands~touching-files:~$ /challenge/run 
Success! Here is your flag:
pwn.college{4zXhKKsolczmpQ2xeEQS5uvfn9O.dBzM4QDLwIjN0czW}

```
- - -
### Challenge 7: removing files.
We learn about the `rm` command that removes files in the argument.
```
hacker@commands~removing-files:~$ rm delete_me 
hacker@commands~removing-files:~$ /challenge/check 
Excellent removal. Here is your reward:
pwn.college{ciDDLVoZxzfzdsk4DeH7Yktrl4S.dZTOwUDLwIjN0czW}

```

### Challenge 8: hidden files.
We learn about the `ls` command, used with the `-a` flag which lists all the hidden files as well.
```
hacker@commands~hidden-files:~$ ls -a /
.  ..  .dockerenv  .flag-108802358014113  bin  boot  challenge  dev  etc  home  lib  lib32  lib64  libx32  media  mnt  nix  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ cat .flag-108802358014113
pwn.college{EeBggjjag0PpfsUB_sIl7T3ic0z.dBTN4QDLwIjN0czW}

```
- - - 

