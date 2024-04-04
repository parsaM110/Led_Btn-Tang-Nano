based on video : https://www.youtube.com/watch?v=F5hlv3XTcO0 by `xesscorp`

![image](https://github.com/parsaM110/Led_Btn-Tang-Nano-1K/assets/101204725/d2a94e9b-6ece-4fe1-b151-b4f2907243b2)


because the impl is on SRAM ,  after the power got cut off it backs to default mode

no need for any type of programmer ( just standard tyep c connector ) | at first got problem:
```diff
Info:	Cable found:  USB Debugger A/0/290/null (USB location:290)
Info:	Cable found:  USB Debugger A/1/289/null (USB location:289)
Info:	Cost 1.73 second(s)
:	 
Info:	Scanning!
Info:	Target Cable: USB Debugger A/0/290/null@2.5MHz
-Error:	No Gowin devices found!
Info:	Cost 10.42 second(s)
:	 
Info:	Cable found:  USB Debugger A/0/290/null (USB location:290)
Info:	Cable found:  USB Debugger A/1/289/null (USB location:289)
Info:	Cost 0.69 second(s)
:	 
Info:	Scanning!
Info:	Target Cable: USB Debugger A/1/289/null@2.5MHz
Info:	1 device(s) found!
Info:	Cost 0.36 second(s)
```

at official documentaion of tang nano there was a link for downloading the software programmer :
https://wiki.sipeed.com/hardware/en/tang/Tang-Nano-1K/Nano-1k.html

which lead to these :
- https://dl.sipeed.com/shareURL/TANG/programmer
- https://mega.nz/folder/A8g1Hb4J#WcuoqvbpasKlVB8-YEpWPA/folder/opp0STJK


