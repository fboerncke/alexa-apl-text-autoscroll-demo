# Alexa APL: Autoscroll text demo with Time and String.slice


## Description

This example shows how to autoscroll text in APL with Time and String methods. 

The approach does not make use of APL commands and proceeds to work while Alexa is listening or talking.


## APL 1.5

With APL 1.5 we received an new method String.length() which made text scrolling easier. See the example "APL_1_5.json" for how to do it.


## APL 1.4

Prior to APL 1.5 we needed a workaround to achieve this effect: you had to count the numbers of characters within your string and use the result in your code. See code example "APL_1_4.json" for how to do it.


## APL bug on some older devices

Some older devices with a non up to date firmware had trouble with processing special characters or German Umlauts ("äöüÄÖÜ"). The code examples shown above will crash the APL on these devices.

Though the bug has been fixed already it may still occur on devices with an older firmware.


## Other solutions

[Another approach for scrolling texts](https://github.com/xeladotbe/apl-playground/blob/master/text-overflow-marquee.json) using vector graphics has been demonstrated by Alexander Martin (@xeladotbe).

