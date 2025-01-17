
1.14" ST7789V IPS-LCD:
Resolution: 135 x 240, high density 260 ppi
4-wire SPI interface, working power supply: 3.3V
Full color TFT display with 1.14" diagonal, drive: ST7789


Installation instructions are really bad. I had it working at some point and then the screen was dead.
2 weeks after i found why...
Change the following lines in the User_Setup_Select.h file...
in c:\Users\<%username%>\Documents\Arduino\libraries\TFT_eSPI\
//#include <User_Setup.h> // Default setup is root library folder
#include <User_Setups/Setup25_TTGO_T_Display.h> // Setup file for ESP32 and TTGO T-Display ST7789V SPI bus TFT


ESP32: Send Messages to WhatsApp
https://randomnerdtutorials.com/esp32-send-messages-whatsapp/


bold: *
Newline: %0A
Space: %20
Emoji: %F0%9F%92%A6
SoS:%F0%9F%86%98
Achtung: %E2%9A%A0
Light bulb: %F0%9F%92%A1
CHEERING MEGAPHONE: %F0%9F%93%A3

https://api.callmebot.com/whatsapp.php?phone=xxx&text=%E2%9A%A0*FermentationControl:*+%0A+Compressor+is+overheated:+*45%C2%B0C!*&apikey=6942851

https://api.callmebot.com/whatsapp.php?phone=xxx&text=%E2%9A%A0*FermentationControl:*+%0A+System+restarted+at+:+*2024-10-10+14:49*&apikey=6942851

https://api.callmebot.com/whatsapp.php?phone=xxx&apikey=6942851&text=*ClimaControl:*%0ATemp+is+under+20%C2%B0C!%0Ahttp://192.168.178.131

https://api.callmebot.com/whatsapp.php?phone=xxx&text=This+is+a+test&apikey=6942851

https://api.callmebot.com/whatsapp.php?phonexxx&text=ClimaControl:+Temp+is+under+20%C2%B0C!&apikey=6942851

https://api.callmebot.com/whatsapp.php?phone=xxx&text=FermentationControl:+Compressor+is+overheted+24%C2%B0C!&apikey=6942851
