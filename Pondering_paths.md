## The Root
The description of the challenge told that the path of a file or folder starting from root directory to that file or folder is called the absolute path. The challenge asked to run 'pwn' from absolute path so i did that to get the flag.

The commands :-<br/>
` hacker@paths~the-root:~$ /pwn `<br/> 
` BOOM!!! `<br/>
` Here is your flag: `<br/>
` pwn.college{s4v0hQFNVRd-pMLQUxhNByBEz5D.dhzN5QDLwIjN0czW} `

- - -

## Program and absolute paths
This challenge is exact same as the last one except here we have to run 'run' which whose absolute path is '/challenge/run' , so after running it from the absolute path i got the flag.

The commands :- <br/>
`hacker@paths~program-and-absolute-paths:~$ /challenge/run`<br/>
`Correct!!!`<br/>
`/challenge/run is an absolute path! Here is your flag:`<br/>
`pwn.college{kQhdP3Z8F0HPOKr-RY_5b7VbtvQ.dVDN1QDLwIjN0czW}`<br/>

## Position thy self
The challenge told me to run /challenge/run from a specific path which it will tell after i try to run it which i did , it told me to run it from root directory. i did cd / to go into root directory and then ran /challenge/run which gave me the flag.

The commands :-

![image](https://i.imgur.com/LqbTpAq.png)

- - -

## Position elsewhere
This is the same as previous challenge expect it gave me the path '/sys/kernel/' to run /challenge/run from to get the flag.

The commands :-

![image](https://i.imgur.com/gGL8MQb.png)

- - -

## Positon yet elsewhere
This is same as previous two as well expect here it gave me the path /var/log to cd into before invoking /challenge/run to get the flag.

The commands :-

![image](https://i.imgur.com/2vJ09Wx.png)

- - -

## implicit relative paths, from /
In this challenge it wanted me to use a relative path to run /challenge/run while being in the / directory and the hint was that the relative path starts from c so i used ls to see all the directories in / directory , there was only one directory starting with c which was challenge so i used 'challenge/run' as it started with c and was a relative path.

The commands :-

![image](https://i.imgur.com/hIt7NuQ.png)

- - -

## explicit relative paths, from /
This challenge asked me to use '.' in my relative path to run /challenge/run so i used to cd to go to root directory first and used ./challenge/run as instructed to get the flag.

The commands :-

![image](https://i.imgur.com/ENxyYco.png)

- - -

## implicit relative path 
The challenge tells me to use '.' to run 'run' while being in the current directory as 'run' , i first missed the part that i needed to be in the same directory but after that i used cd to get into /challenge/ then used ./run to invoke 'run' using '.' command.

The commands :-

![image](https://i.imgur.com/1PtxTNh.png)

- - -

## home sweet home
The challenge simply told me to run /challenge/run with an arguments whose path is inside my home directory and total characters should be less that three characters so i used ~ for home directory and a as the file name where the copy of flag will be stored inside home directory hence fulfilling the conditions and getting the flag.

The commands :-

![image](https://i.imgur.com/pxI3edI.png)

