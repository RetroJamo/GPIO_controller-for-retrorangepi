# GPIO_controller-for-retrorangepi
# forked version to utilize additional GPIO to have 10 buttons per player vs. original 8

go to your command line by pressing the F4 key from emulationstation the type the following commands:

$ wget https://github.com/pjmcardle/GPIO_controller-for-retrorangepi/raw/master/TZGPIO.tar.gz

$ tar -xzvf TZGPIO.tar.gz

$ cd gpio

$ chmod +x install.sh

$ sudo ./install.sh

$ sudo reboot

now check to see if your controllers are recognized in emulationstation after your system restarts

this image are to plug GPIO pins
* credits mk_arcade_joystick
https://raw.githubusercontent.com/recalbox/mk_arcade_joystick_rpi/master/wiki/images/mk_joystick_arcade_GPIOsb%2B.png

You can also add the following 4 button inputs beyond what the image above shows:
Player 1: pins 3 & 27
Player 2: pins 5 & 28

Open the file above RetrOrangePi_GPIO_Pinout.xlsx to see all locations.

Happy gaming!
