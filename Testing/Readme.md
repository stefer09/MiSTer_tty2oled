**Testing-Version**  
  
Updated tty2oled Daemon Script, new Scripts and updated Arduino Code.  
Use the INI File and the tty2oled Script from this folder.  
Remove ".testing" from the filenames.  
  
Most important change is the command response back from the tty2oled ESP to the tty2oled Daemon.  
When a command is processed by the ESP a "ttyack" is sent back which the tty2oled Daemon can process.  
  
The file tty2oled_cc.testing.sh (remove .testing) is the tty2oled Control Center.  
From here you can start/stop/restart the tty2oled Daemon, start an Picture Slideshow, start OTA or Reset the ESP32.  
Take a look.  
  
The file Clock01.ps1 is an PowerShell Script showing your Windows System Time.  
The file tty2oled_GEO.testing.sh (remove .testing) is the same for Linux Systems.  
  
Report Issues here:  
https://misterfpga.org/viewtopic.php?p=28397  

