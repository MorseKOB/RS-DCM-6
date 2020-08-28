# RS-DCM-6
Radio Shack (TANDY) Direct Connect Modem DCM-6 used for dial-up MORSE telegraphy

This contains information about the DCM-6 modem that was the 'go-to' device for dial-up telegraphy.

Hopefully this provides useful info about the device and how it was used. Some of the information presented 
is copied from manuals that have their own copyrights, but Radio Shack is out of business, so I 
couldn't ask their permission. Others, like Texas Instruments and National Simiconductor, were 
pulled from their website.

Hopefully it will be obvious where the content is from me and where it is from another source. I 
am not trying to ingringe on any copyrights by pulling this useful information together.

Thank you to https://www.digchip.com/ for most of the PDF datasheet copies.

## About the Device
The Radio Shack (Tandy Computer Products) DCM-6 (#26-1393) is a 300 BUAD MODEM device that 
includes a jack for an acustic coupler. The acustic coupler/cups was sold separately (#26-3805).

An important aspect of the device (as was common at the time it was new) is that it is passive (dumb). 
What that means is that the digital (RS-232) signals are converted to/from FSK tones without any other processing. 
Newer MODEMs incorporate processors that 'look' at the incoming and outgoing data for things 
like the 'AT' command set (to tell the MODEM to do things and set parameters) and convert the incoming 
tones to characters, rather than simply setting the digital signal to high or low (mark or space). The 'smart' 
MODEMs don't work, because the dail-up telegraphy relies on the duration of the tone being sent to 
follow the key down/up duration of the sender. This will not have a start-bit/data-bits/stop-bit format and 
the 'intellegent' MODEMs can't deal with it.



