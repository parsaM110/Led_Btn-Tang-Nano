based on video : https://www.youtube.com/watch?v=F5hlv3XTcO0 by `xesscorp` ( my board is tang-nano  which is simillar to tang-nano-1k)
you pick it when you are creating project :
 ![image](https://github.com/parsaM110/Led_Btn-Tang-Nano/assets/101204725/3fddcc3c-1ba9-4157-96e7-4a413bcc3d2a)


![image](https://github.com/parsaM110/Led_Btn-Tang-Nano-1K/assets/101204725/d2a94e9b-6ece-4fe1-b151-b4f2907243b2)


because the impl is on SRAM ,  after the power got cut off it backs to default mode

no need for any type of programmer ( just standard tyep c connector ) 
> Yes, and Tang Nano boards ship with JTAG + USB debugger on board. It's quite nice.
>> ekahn : http://www.thereminworld.com/Forums/T/32203/lets-design-and-build-cool-but-expensive-fpga-based-theremin?post=222961
at first got problem:
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
- https://dl.sipeed.com/shareURL/TANG/Nano
- https://mega.nz/folder/A8g1Hb4J#WcuoqvbpasKlVB8-YEpWPA/folder/opp0STJK

### 📌 there is also other ways to program tang-nano-1k fpga board
* using gowin (http://www.gowinsemi.com.cn/faq.aspx)
* one way is to use openfpgalaoder (open-source) : which seems to support all kind of tang-nano-boards (my board : https://wiki.sipeed.com/hardware/en/tang/Tang-Nano/Nano.html)
  * https://github.com/trabucayre/openFPGALoader (there is a list of compatibility boards which tang-nano is included)
  * https://www.youtube.com/watch?v=Gh9VfCvTWck (video is for tang-nano-4k)
  * https://www.reddit.com/r/GowinFPGA/comments/106si63/asking_for_help_tang_nano_9k_programmer_linux/
* there seems to be another way using oss-cad-suite-build (which is from YosisHQ) which is used by platform.io and lushaylabs but seems it is for tang-nano-9k only
  * https://learn.lushaylabs.com/
  * https://www.youtube.com/watch?v=Y8koTqfXN3M
