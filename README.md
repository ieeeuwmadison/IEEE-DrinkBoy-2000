#Instruction
1.	Install Arduino IDE if you have not done so.
2.	Install Arduino Nano clone driver.
3.	Install Screen library Adafruit-GFX-Library and Adafruit_SSD1306. Open Arduino IDE->Sketch->Include Library->Manage Libraries and search for those libraries.
4.	Go to the directory of libraries you just installed likely at (Documents\Arduino\libraries\Adafruit_SSD1306\). Open Adafruit_SSD1206.h and edit the following.
a.	Uncomment this line (line 28).
i.	#define SSD1306_128_64 ///< DEPRECTAED: old way to specify 128x64 screen
b.	Comment this line (line 29).
i.	//#define SSD1306_128_32   ///< DEPRECATED: old way to specify 128x32 screen
5.	Plug your Arduino Nano with a Macro USB cable (not Micro USB!) to your PC. 
6.	Set up IDE for uploading codes to the board.
a.	In Arduino IDE->Tools->Board, select Arduino Nano.
b.	In Arduino IDE->Tools->Processor, select ATmega328P (Old Bootloader).
c.	In Arduino IDE->Tools->Port, select whichever COM it is (you will likely see only one).
7.	Download the code from this GitHub and study it!
a.	If you want to test each component, here is GitHub for it.
8.	Change the code as needed and enjoy drinking!
