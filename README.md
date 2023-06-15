# ESP32_KeyPad_4x20_LCD_WS2815
KeyPad (0-9,*,#) and 4x20 LCD WS2815 stand alone controllor
KeyPad and 4x20 LCD WS2815 stand alone controllor I own Pittsburgh Event Lighting (https://www.pittsburgheventlighting.com).
My close friend produces hard cider and opened a new location/bar.
I installed a sound system and placed WS2815 on the display shelves.
************    CONTROLLOR    ************  
My goals for the controller are: 
• Reliability 
• Stand-alone operation 
• Simple control with ease of use 
• Custom scenes and chases 
• 1-99 keypad custom for selecting scenes/chases.
• LCD display 
o Scene # and description i.e. "Rainbow Chase" 
o Dimmer level 1-100 o Chase speed 1-100 
• Four Hardware debounced Arcade switches 
o Dimmer / Brightness control 
o Speed control for active (chase) scenes
*********************************************
//  June_14_2023
//  TO-DO  LIST
//  Fix Scences & Chases   1 to 59  Good \  Done
//  80 to 90  Holiday Theme
//  Fixed Lines 1362 to 1382  Dim & Speed  \  Done
//  Find a Better Way to Control SPEED, No-Delay Commands  /  Done
//   Test Frames per seconds  max 400   /  Done
//  Code Commented, Good.    /  Done
//	Code optimized for speed and readability.   /  Done
//	*****************		Next:           *****************	 
//	Keys 80 to 100 Holiday and Custom Scenes & Chases.
//	USB Keypad interface
