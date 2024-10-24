## Chaining with Semicolons
Learnt the use of `;` and how it can be used to run multiple commands in a single line.<br>
It has the same use as when we press enter to run a command and then it terminates.<br>
```bash
hacker@chaining~chaining-with-semicolons:~$ /challenge/pwn;/challenge/college
Yes! You chained /challenge/pwn and /challenge/college! Here is your flag:
pwn.college{oJIyOCw36RCTnw4YnteB0apFnmP.dVTN4QDLzYTN0czW}
```
## Your First Shell Script
In this challenge we had to make a shell script with the name x.sh so i used to nano to create it and put `` /challenge/pwn
/challenge/college `` inside the shell script as the challenge demanded to get the flag
```bash
hacker@chaining~your-first-shell-script:~$ touch x.sh
hacker@chaining~your-first-shell-script:~$ nano x.sh
hacker@chaining~your-first-shell-script:~$ bash x.sh
Great job, you've written your first shell script! Here is the flag:
pwn.college{szsDHE7j3oUIOPZk1XCUBuYunKB.dFzN4QDLzYTN0czW}
```
## Redirecting Script Output
Learnt that the whole script execution acts as a single command then we can redirect its output, error, input like we learned previously.<br>
i put `` /challenge/pwn
/challenge/college `` inside the script.
So as the challenge instructed i redirected the output of a script to the input of a file.<br>
```bash
hacker@chaining~redirecting-script-output:~$ touch script.sh
hacker@chaining~redirecting-script-output:~$ nano script.sh
hacker@chaining~redirecting-script-output:~$ bash script.sh | /challenge/solve
Correct! Here is your flag:
pwn.college{YxHm1RWE0tw7wp9ZwoNCHZRX-9i.dhTM5QDLzYTN0czW}
```
## Executable Shell Scripts
Learnt that we can skip the `bash` command and rather just execute the script like `./script.sh` and get the output.<br>
We also need to give it permissions via `chmod` command.<br>
```bash
hacker@chaining~executable-shell-scripts:~$ touch a_minor.sh
hacker@chaining~executable-shell-scripts:~$ nano a_minor.sh
hacker@chaining~executable-shell-scripts:~$ chmod +x a_minor.sh
hacker@chaining~executable-shell-scripts:~$ ./a_minor.sh
Congratulations on your shell script execution! Your flag:
pwn.college{4Qs2QWXINHlYEQ_s6uAaD00M3b1.dRzNyUDLwIjN0czW}
```
