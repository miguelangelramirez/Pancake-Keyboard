![Pancake Legend Seal](https://github.com/PancakeLegend/Keyboards/blob/master/Pancake%20Legend%20Seal.svg)

## Warning: Reprogram your keyboard at your own risk.

If you've never flashed a micro-controller, this may be daunting.

# Changing the Keymap

Keymap and Firmware files for your keyboard are located in the Code tab of this Repo. Upload the Keymap file for your keyboard to the [Keyboard Firmware Builder website](http://kbfirmware.com/).

![KBFirmware.com](https://i.imgur.com/97p7oPH.png)

Add layers, macros, or just rearrange a few keys. Just don't change anything in the **Wiring** or **Pins** tabs as this can result in a non-functional keyboard after flashing.

To change the function of a key, go to the **Keymap** tab and click the key you want to change in the layout. Then either press the key that you want it to be on your keyboard, or go into the configuration.

![Change your keymap](https://i.imgur.com/rgNEqTk.png)

The configuation options of QMK are deep. To get the most out of QMK and the Keyboard Firmware Builder tool you will need to look into the [QMK documentation](https://docs.qmk.fm/#/features). Understanding the [list of all the Keycodes](https://docs.qmk.fm/#/keycodes) will be helpful to you. 

Save your layout in the **Settings** tab.

Go to the **Compile** tab to download your updated firmware **.hex** file.

# Flashing the Firmware

## Windows

On Windows use **AVRDudess** to flash your keyboard, but first we need to set it up.

### Setup

**1.** Install **Bash Shell** [[Guide]](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)

**2.** Install **WinAVR** [[Download]](https://sourceforge.net/projects/winavr/)

**3.** Install **AVRDudess** [[Download]](http://blog.zakkemble.net/avrdudess-a-gui-for-avrdude/)

**4.** Copy the four **libusb0** files from your **WinAVR** folder...

![WinAVR Folder](https://i.imgur.com/bEYz3uO.png)


**5.** ...and paste them into your **AVRDudess** folder.

![AVRDudess Folder](https://i.imgur.com/9lrj6nO.png)

### Flashing with AVRDudess

**6.** In **AVRDudess**, change the **Programmer** and **MCU** dropdowns to match the following image, and select the **.hex** file that you want to flash to your keyboard.

![AVRDudess 01](https://i.imgur.com/ALl6vle.png)

**7.** Before putting your keyboard into bootloader mode, check the **Port** dropdown to see which COM port connections currently exist.

![AVRDudess 02](https://i.imgur.com/4FPLSlL.png)

**8.** Briefly connect the exposed pins on the underside of your keyboard with something metal to put it into bootloader mode. These 2 pins are the Ground (GND) and Reset (RST) pins of the Pro-Micro. The keyboard will remain in bootloader mode for only 8 seconds if it doesn't start the flashing process, so the next 2 steps need to be performed quickly.

![Keyboard Reset Pins](https://i.imgur.com/h5n1heN.jpg)

**9.** With the keyboard now in bootloader mode go to the **Port** dropdown again and you will see a new connection. In this case it's COM10, but yours may be different. Select it.

![AVRDudess 03](https://i.imgur.com/AppxZQZ.png)

**10.**  Click the **Program!** button. It only takes a few seconds to write the firmware to your keyboard.

![Program!](https://i.imgur.com/OCPGTBf.png)

## Congratulations

You've now updated your keyboard firmware!
