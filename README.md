
--------------------------------------
ESP8266 WebHost for PS5 FW4xx to FW5xx
--------------------------------------

This is a webhost for esp8266 chip(i haven't tested esp32 yet) for firmwares FW4xx to FW5xx. 
It's the webhost UMTX2 made by Idlesauce that comes with some adjustment.
I did put Mouuu㋡'s additional "pop up feature notification", that is his genius workaround regarding Etahen's freezing problem, specially the toolbox feature loading after injecting it.
Even though I no longer use etahen since December last year, I decided to keep Mouuu㋡'s script on it.
I also did put vladimir-cucu's "unlimited payloads feature" by using the ps5's internal storage. All credits to him regarding to this awesome idea.
This webhost also has the "user's guide" shortcut support, it will be alot easier for the users to run a preloaded kstuff and install a media tab shortcut icon.
It also comes with "lapy jb daemon v1.2" preloaded payload, so users can install and run ps5xplorer app without etahen(credits to ArkSama) and simply copy all the needed payloads they want internally.

<img width="2048" height="1102" alt="esppic" src="https://github.com/user-attachments/assets/5a97cb53-9f4e-4110-adc3-dd7b92a5f1df" />


--------------------------------------
This webhost comes with 7 payloads initially:
--------------------------------------

 - kstuff 1.6.7
 - ftp drakmor 1.15 (to transfer payloads via ftp)
 - display user id (to know where to put the payloads)
 - Browser appcache remover
 - shadowmountplus1.6beta9.elf
 - nanodnsv0.2.elf
 - lapy_jb_daemonv1.2.elf (to enable ps5xplorer app and transfer payloads via usb to internal)

--------------------------------------
What is needed?
--------------------------------------

- an esp8266 mini chip (a regular size esp8266 may work or an esp32, but I haven't tested it yet)
- a node mcu pyflasher (https://github.com/marcelstoer/nodemcu-pyflasher)
- binfile (ESP8266PS5UMTX2_V2SU.bin)
- media tab shortcut icon installer (no need to run exploit via user's guide shortcut next time)
- my payload package as of 05312026 https://www.mediafire.com/file/jtr14oehohora51/esp-payloads.zip/file (optional)


--------------------------------------
Wifi Details:
--------------------------------------

- SSID: PS5JBPinas
- Password: 12345678

--------------------------------------
How to setup?
--------------------------------------

1. download binfile (ESP8266PS5UMTX2_V2SU.bin), node mcu pyflasher (https://github.com/marcelstoer/nodemcu-pyflasher), Lapy's ps5xplorer app(https://pkg-zone.com/details/LAPY20011), media tab shortcut icon installer fpkg and my payload package https://www.mediafire.com/file/jtr14oehohora51/esp-payloads.zip/file (optional)
2. flash your esp8266 with ESP8266PS5UMTX2_V2SU.bin via node mcu pyflasher
3. connect your ps5 into it (use Wifi Details)
4. go to user's guide, run the jailbreak, load kstuff 1.6.7, lapy_jb_daemonv1.2 and display user id payload (remember the id)
5. plug your usb with Lapy's ps5xplorer app fpkg, media tab shortcut icon installer fpkg and the payload package already extracted inside
6. install ps5xplorer app and the media tab shortcut icon
7. run ps5xplorer and copy all the payload package on the designated path internally (you can add and delete payloads that you want)

   payload path:
   - /user/home/(user-id)/webkit/shell/esp-payloads
     
   payload path example:
   - /user/home/(user-id)/webkit/shell/esp-payloads/kstuff1.6.7.elf
  
--------------------------------------
Special Thanks
--------------------------------------

Mouuu㋡ https://github.com/ps5xploit
vladimir-cucu https://github.com/vladimir-cucu
Arksama https://github.com/ArkSama
Idlesauce https://github.com/idlesauce
Stooged https://github.com/stooged
Echostretch https://github.com/EchoStretch
Drakmor https://github.com/drakmor
TheOfficialFloW https://github.com/theofficialflow
Pippo, kerrdec97, Mr.Cat all devs, dumpers, testers

PS4/PS5 Jailbreak Pinas
https://www.facebook.com/groups/390633592648807
https://www.facebook.com/groups/1011520630219418

  
 









