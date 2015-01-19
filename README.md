pi-shutdown
===========

Shutdown/reboot(/power on) Raspberry Pi with pushbutton

## Usage:
Connect pushbutton to GPIO pin 5 and ground then run:
```
sudo python pishutdown.py
```

When button is pressed for less than 3 seconds, Pi reboots. If pressed for more than 3 seconds it shuts down.
While shut down, if button is connected to GPIO pin 5, then pressing the button powers on Pi.

