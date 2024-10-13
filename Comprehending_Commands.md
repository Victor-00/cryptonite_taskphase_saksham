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
