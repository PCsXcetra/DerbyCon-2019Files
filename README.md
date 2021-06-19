# DerbyCon-2019Files
This is a group of tools that I was planning on releasing During a Derbycon 2019 talk if it was accepted or with a blogpost if not.
I have also included the malware samples along with the layers of decoding for each sample. This folder is a 7Zip and password protected with the normal password of infected.

These are malicious samples so use all caution. I am not responsible if you extract and run these files and infect yourself.

That being said my tools are designed so you don't have to run the malicious code to decode what it is doing.

2019-11-15 Uploaded just the tools 7Zipped no password.
2020-02-25 Uploaded just the tools 7Zipped No password. Some tools have been updated but not all.

You can view the blogpost that these tools go with here https://pcsxcetrasupport3.wordpress.com/2019/07/07/those-pesky-powershell-shellcodes-and-how-to-understand-them/

Blog post using these tools for decoding multi rounds of Shikata Ga Nai encoding https://pcsxcetrasupport3.wordpress.com/2020/02/25/more-adventures-with-shell-code-and-the-shikata-ga-nai-encoder/

2021-03-13 Added experimental tool to build hashses based on api name and dll name. May still have some errors.
File name is HashStringUsingKnownAlgos.7z   password is "clean"


Update: 2021-05-28
Updated Extract-IP-From-Meterpreter-ShellCode to version 1_0_0_3342 to handle meterpeter x64 wininet shellcode that puts the IP in the middle instead of the end of the shellcode.
file name is Extract-IP-From-Meterpreter-ShellCode1_0_0_3342.7z password is clean .

Twitter reference to a Blog post on type. https://twitter.com/DmitriyMelikov/status/1397922972078276611

Upadte: 2021-06-19
Updated Extract-IP-From-Meterpreter-ShellCode to version 1_0_0_3343 to handle WS_32 32 bit difference in the way the bind port and normal port with out bind API are calculated.
See twitter screenshot here. 
