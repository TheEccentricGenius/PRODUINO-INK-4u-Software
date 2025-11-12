# How to add the INK 4u board to the Arduino IDE.

If you haven't already installed DxCore install it using these instructions, <i><a href="https://github.com/SpenceKonde/DxCore/blob/master/Installation.md#boards-manager-installation-now-strongly-recommended-unless-helping-with-core-development">installing DxCore.</a></i>

Locate your Arduino15 folder using these instructions, <i><a href="https://support.arduino.cc/hc/en-us/articles/360018448279-Open-the-Arduino15-folder">locating the Arduino15 folder.</a></i>

Locate the DxCore in the packages folder, it should look somewhat like the picture below.
</br>
<img src="https://github.com/user-attachments/assets/c2e16436-ec51-4670-afee-9fe49067674f" width="75%" height="75%">

Download this zip package.
Copy the variants and bootloader folders from this zip package into the directory you have just located.
Copy the boards.txt from this package and use it to replace the boards.txt in your DxCore install.

Close and reopen the Arduino IDE, you should have a menu option like one of the pictures below.
</br>
<img src="https://github.com/user-attachments/assets/da545b15-00d8-4201-b1c8-34300f24233f" width="75%" height="75%">
<br><i>If using Arduino IDE version 1.8.19 or below.</i></br>
</br>

<img src="https://github.com/user-attachments/assets/5ef1940a-260a-41ae-afed-3425b8d3e5d2" width="75%" height="75%">
<br><i>If using Arduino IDE version 2.0 or higher.</i></br>
