# BTLO - Reversing Engineering
## A Classic Injection

### Flags
```
1 - What is the name of the compiler used to generate the EXE? 
Microsoft Visual C++ 8

2 - This malware, when executed, sleeps for some time. What is the sleep time in minutes?
3

3 - After the sleep time, it prompts for user password, what is the correct password?
btlo

4 - What is the size of the shellcode?
473

5 - Shellcode injection involves three important windows API. What is the name of the API Call used?
CreateRemoteThread

6 - What is the name of the victim process?
nslookup.exe

7 - What is the file created by the sample?
C:\Windows\Temp\btlo.txt

8 - What is the message in the created file?
Welcome to BTLO!

9 - What is the program that the shellcode used to create and write this file?
powershell.exe
```
