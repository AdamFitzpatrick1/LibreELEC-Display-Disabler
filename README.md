# LibreELEC-Display-Disabler

Disable the internal display on a Laptop when running LibreELEC. Allows the use of the native resolution for the connected TV (prevents screen mirroring).

You may need to change the device names for the display and output depending on your hardware.

To do this: 

1. Find the IP of the computer using system settings
2. Connect using SSH
3. Run xrandr -q

To run the script on boot:

Run the following commands (Whilst connected with SSH): 

1. nano /storage/.config/autostart.sh
2. Type the code in as it appears in the shell script
3. Press ctrl+x, press the Y key and then enter
