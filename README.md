# Text-Talky

This is a handheld mini texting device that communicates using radio, three of them to be exact. This allows them to be used offline without an internet connection though it does mean that they have a limited range of about a few kilometers. I chose to design it kind of like a Nintendo ds where they can fold in when not in use, but for the input I chose a qwerty pcb keyboard instead of a touchscreen display the display like everything else will be connected to an esp the main processor for the project. Here is more information about the different components of the Text Talky.

## DISPLAY

the display is a 2.4 Inch TFT LCD Display Module. I chose this display module specifically because it had only a few pins. This is important because the Esp 32 doesn't have too many digital io pins meaning as I design, I have to actively rashin the available pins. besides having few pins, the display also has full RGB is compatible with the Esp 32 support and is relatively the size I want the whole project to be. The TFT display will be mounted on the top half of the 3d printed case and connected to the lower half where the Esp is with perfectly aligned jumper cables.


![Display Module](Images/i_imp3qr6x00.jpg)
