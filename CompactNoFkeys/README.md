# The first model

Compact keyboard without numpad and F1-F12 keys with arrows squished under Return key. I think it's called 63%.

![visual](https://raw.githubusercontent.com/paulogliwa/Keyboard/master/CompactNoFkeys/Images/RoughVisualisation.jpg)   
*This may not be the final look*
![updated after using the original layout](https://raw.githubusercontent.com/paulogliwa/Keyboard/master/CompactNoFkeys/Images/layoutRework.jpg)  (https://raw.githubusercontent.com/paulogliwa/Keyboard/master/CompactNoFkeys/Images/layoutReworkLayer2.png)  

# Parts list
+ 1N4148 DIODES
+ Arduino Pro Micro (ATMega 32u4)

# DEVNOTES
+ diodes in the oryginal design were flipped (row to column)
+ first rigid prototype has problems with the following keys (4 - not working bad solder, 9 - not working bad solder, menu - not working, home - not working bad switch)
+ second layer needs a overhaul - when i press CapsLock my F1-F12 keys are active, but i should also have ctrl alt delete and other common combinations active, because right now I have no way of clicking alt+F4 or similar
+ i propably dont need the extra key next to the backspace so i can move delete to home, |\ switch with backspace, home and end move one key down, and make backspace wider 