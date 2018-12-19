![Pancake Legend Seal](https://github.com/PancakeLegend/Keyboards/blob/master/Pancake%20Legend%20Seal.svg)

## Please read the entire guide before beginning assembly

![Completed Keyboard](https://i.imgur.com/UJrK6nh.jpg)

**Estimated assembly time:** 3-4 hours

Assembly of the keyboard requires that the Solderless USB braided cable is already assembled. If you don't have an assembled cable, [do that first](https://github.com/PancakeLegend/Keyboards/wiki/Solderless-USB-Micro-cable:-Assembly-guide). 

# You will need:

* PLMiT Keyboard Kit
* Soldering iron and solder
* Flush cutters
* A hard surface
* Electrical tape
* Small screwdriver
* Tweezers
* Micro USB cable
* Nail clippers

# What's in the kit:

![Kit - Layers](https://i.imgur.com/OvMLE6D.jpg)

* PCB
* Top Plate
* Stainless Steel sandwich layer
* Paper insulator
* Adhesive velvet foam base pad

![Kit - Parts](https://i.imgur.com/wk68WqU.jpg)

* Arduino Pro-Micro
* Header pins
* Header pin holder
* USB support staple
* USB cable clip
* Diodes
* Diode bending tool
* Stabilizer parts

# 1. Assemble and insert the stabilizer

![Insert the slider into the housing](https://i.imgur.com/GElYsMk.jpg)
**1-1** Insert the slider up into the housing from the bottom. Take note of the orientation of the notch in the back of the slider.

![Lube the stabilizer bar](https://i.imgur.com/yevEuC0.jpg)
**1-2** If you wish to lube your stabilizer, add dielectric grease to the end of the stabilizer bar before inserting into the slider.

![Insert the stabilizer bar](https://i.imgur.com/K8qFwPm.jpg)
**1-3** Insert the stabilizer bar through the front of the housing and into the slider. Once inserted, push it down into the clip at the front of the housing. Test that it moves freely then repeat for the other side.

![Arrange the top plate and the stabilizer as shown.](https://i.imgur.com/SHELuAS.jpg)
**1-4** Arrange the top plate and the stabilizer as shown.

![Insert the stabilizer](https://i.imgur.com/gKxaVa7.jpg)
**1-5** Insert the stabilizer into the top plate with the bar underneath and the clip above the plate, then push down at the front to lock it in place.

# 2. Diodes

![Bending diodes](https://i.imgur.com/XUVTRvt.jpg)
**2-1** Cut the diode strip into pairs.  Place a pair on top of the diode bending tool, then fold over all 4 legs at the same time with the other hand. Repeat until all the diodes are bent.

![Insert the diodes](https://i.imgur.com/tBKdWAO.jpg)
**2-2** Insert one row of diodes. Take note of the orientation of the PCB, insert the diodes from the side which has the component numbers printed. The end of the diode with the black line should be inserted into the holes with the square solder pads as shown. After you insert the diode, bend the legs out slightly on the other side to keep them in place when you flip the board over to solder.

![Solder the diodes](https://i.imgur.com/ymjkBsr.jpg)
**2-3** Insert then solder the diodes one row at a time to prevent the legs getting in the way. Use flush cutters to cut the legs close to the PCB after soldering each row.

# 3. The USB support staple

The purpose of the staple is to prevent the USB jack on the Pro-Micro from being ripped out if the keyboard cord gets yanked. When in place it should be touching against the USB jack and holding it in place from beneath.

![Insert the staple](https://i.imgur.com/A2Jrtso.jpg)
**3-1** Insert the staple into the holes with the square solder pads as shown. Take not of the orientation of the PCB. Solder the staple in from the bottom making sure that it is inserted all the way in then cut the legs with flush cutters.



# 4. Prepare the Pro-Micro

![Use the holder to keep the headers in place for soldering](https://i.imgur.com/dYky8iA.jpg)
**4-1** Insert the header pins into the header pin tool to hold them in place for soldering. The pins don't need to go all the way in to the holder, just enough for them to stay in place. Put the Pro-Micro and headers on a flat hard work surface such as metal or a hard, flat wooden board.

![Check the pins are flush with the bottom](https://i.imgur.com/J3Sjm8i.jpg)
**4-2** Solder the pins at each end of the header from the top side. Flip the Pro-Micro over and check that all the pins are flush with the bottom surface of Pro-Micro PCB. Remove the header tool, flip the Pro-Micro back over and solder all the remaining pins.

![Cut then remove the header spacer](https://i.imgur.com/dqga4ya.jpg)
**4-3** Cut the plastic header pin spacers with your flush cutters, then work the spacers off the pins with a small screwdriver. 

**Caution:** This step can be difficult, it requires significant force to be applied to a delicate component. Be careful and remain patient, slowly work the spacers off. After removal of the spacers, re-straighten any bent pins with long nose pliers if necessary.

![Place electrical tape on the underside of the Pro-Micro](https://i.imgur.com/rguTYhX.jpg)
**4-4** Place electrical tape on the underside of the Pro-Micro.

# 5. Solder the Pro-Micro into the PCB

Before proceeding, do a visual inspection to check that all of your pins have good quality solder connections to the Pro-Micro.

Note that plugging the USB cable into the Pro-Micro the first time can be difficult, so first make sure that it can be plugged and unplugged normally before proceeding.

![Dry fit](https://i.imgur.com/xQVaMy5.jpg)
**5-1** Perform a dry-fit of the Pro-Micro. With the Pro-Micro inserted, the cable clip, USB cable, and the stainless steel sandwich plate in place, check that the Pro-Micro doesn't sit proud of the stainless steel plate. If it isn't flush with the plate, use a small screwdriver to gently adjust the shape of the USB support staple until it can fit together neatly.

![Solder with all the parts in place](https://i.imgur.com/aH2QVkJ.jpg)
**5-2** With all the parts of the dry fit from the previous step in place, flip the board over on the table and solder the 4 corner pins of the Pro-Micro. Apply some pressure to the top of the PCB to keep everything in place. This step is necessary to make sure that the cable can be properly inserted and removed after the Pro-Micro is soldered in place.

![Solder the remaining pins](https://i.imgur.com/T8vK7L6.jpg)
**5-3** Remove the USB cable and clip. Solder the remaining pins of the Pro-Micro then cut the pins with flush cutters.

# 6. Test that it's working

**6-1** Connect your keyboard to an internet connected computer and go to: http://keyboardchecker.com/

![Short the switch pins](https://i.imgur.com/zpSk0z5.jpg)
![Success](https://i.imgur.com/xhwh4b4.jpg)
**6-2** Using a bent piece of wire, carefully short the pads of each key. If everything is working you should see the keys of the on-screen keyboard turning green as you short the switch pads. Do a little chair dance.

Note that the layer keys won't trigger a key when pressed by itself, however when used in conjunction with other keys will trigger those keys as proof that the layer key is functional. The Window/Command key may be intercepted by the system.

If any key doesn't trigger, check that the diode is soldered in and oriented correctly. Check that all the solder joints of the Pro-Micro are of good quality.


# 7. Switches

![Remove PCB mount plastic pins](https://i.imgur.com/LHJ2OOh.jpg)
**7-1** The PCB is designed for plate mount switches, however the only difference between plate mount and PCB mount switches are 2 small plastic locating pins on the bottom to the sides which are easily removed with flush cutters, nail clippers, or a sharp knife. Check which type you have and remove the small plastic pins if necessary. **DO NOT** remove the larger switch stem or metal pins.

**Caution:** If the locating pins aren't removed very close to flush, the remaining dag may prevent the keyboard from fitting together neatly. Take your time and inspect each switch as you go.

![Insert some switches then flip the board over](https://i.imgur.com/kF6Lo5e.jpg)
**7-2** Insert a few switches into the top plate starting with the corners and a few scattered in the middle. Make sure that the top plate is oriented correctly, and that switches are rotated correctly for the pins to fit into the PCB. Then flip the top plate over and put the stainless steel sandwich layer in place. Check that the pins are not bent over.

![Paper insulator and PCB](https://i.imgur.com/1SGrh95.jpg)
**7-3** Align the paper insulating layer on top of the stainless steel plate before putting the PCB on top. You may need to wiggle the PCB to get it to fall into place. If it doesn't go on easily, check that the switches are oriented correctly to be received in the holes and that all pins are fully upright. When the PCB is in place, check that both pins of each switch are poking through the PCB.

**7-4** Solder one pin from each switch. 

![Solder one pin from each switch](https://i.imgur.com/iOpiJG3.jpg)
**7-5** Go back through the switches and re-melt the solder on the first pin and tightly squeeze the switch and the layers of the keyboard together so that sit together squarely and neatly. It's likely that you'll hear a few switches click as they move into place. Then solder the second pin of each of the switches. 

**7-6** Insert all the remaining switches. Be careful to check that the pins are straight before inserting and that they don't bend over during the process. Check that both pins of each switch have come through as you insert them.

**7-7** Repeat steps 7-4 and 7-5 for all the remaining switches.

# 8. Attaching the foam base pad

![Remove the holes](https://i.imgur.com/CK2PUeS.jpg)
**8-1** Remove all the small circle cutouts for the switch stems from the foam pad with tweezers. Put the USB clip in place before proceeding.

**8-2** Starting from the opposite end of the Pro-Micro, peel the backing enough to reveal the first column of switches.

![Attach the foam pad](https://i.imgur.com/LGyyloB.jpg)
**8-3** Carefully align the holes for the first column of switch stems over the stems and lightly press down the pad.

**8-4** Proceed to slowly peel the backing, align the holes to the stems then press the pad into position one column at a time until the pad if fully attached. You may need to lightly stretch or push the foam as you go to maintain alignment with the holes and the stems. 

**8-5** Press the entire pad down firmly.

# Congratulations!

![Completed Keyboard](https://i.imgur.com/2E8flBE.jpg)

Your keyboard is nearly complete. Time to find some great keycaps to go with it!



