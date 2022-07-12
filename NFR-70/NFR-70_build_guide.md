# NFR-70 Quick Build Guide

## Step 1: The Microcontroller

A good thing to start off with, is to test the microcontroller to ensure that everything is working as intended. 

### Step 1.1: Flashing the Microcontroller

First, make sure that you have the [QMK Toolbox](https://github.com/qmk/qmk_toolbox) installed on your machine. Then go to the [Nyhxis keyboard resources repository](https://github.com/Nyhxis/keyboard-resources/tree/main/NFR-70), and download the `nyhxis_nfr_70_via_elite-c.hex` file to your local machine and go into QMK Toolbox and flash the MCU using the firmware hex.

### Step 1.2: Testing the Microcontroller

Then we need to test the microcontroller (MCU). You do this by testing every pair combination of blue and red slots using some sort of keyboard testing software (fx. [VIA](www.usevia.app)), using a tweezer, abit of wire or anything else you have around that can connect the electrical signal.

![](https://i.imgur.com/JihpiSjh.png)

Every combination should then trigger a keypress in the tester, and you're ready to start your build.

## Step 2: Diodes

![pcb-diodes](https://i.imgur.com/wjYhAzUh.jpg)

First, you need to put all the diodes into the back of the PCB. This is easily done by holding the diode between your fingers and gently bent both legs to a 90 degree angle. The holes are roughly 7.5 mm apart, so the legs bent quite naturally at the correct place. Then you simply wanna place it in each of the slots, located near each switch mounting point, like so:

![pcb-diode](https://i.imgur.com/4leEuu1h.jpg)

Make sure that the black stripe on the diode is facing the direction of the small line on the silkscreen.

Now you just need to solder in all of the diodes. I find it easier to solder them in from the front of the PCB (the side with all the legs sticking out) while gently pulilng the legs to ensure the diodes lay as flat on the back as possible. Afterwards, simply cut all of the legs as close to the PCB as you feel comfortable, just to make sure they don't interfere with the switches.

![pcb-diode-cut](https://i.imgur.com/ZHCsG7qh.jpg)

## Step 3: Reset Switch

The next step is to insert the reset switch. This should also be placed from the back of the PCB, in the small slot labelled **SW1** like so:

![reset-switch](https://i.imgur.com/u7p8wnVh.jpg)

This also needs to be soldered in from the, however, the legs are so short that you don't need to worry about cutting these.

![reset-switch-solder](https://i.imgur.com/ofkotlXh.jpg)

## Step 4: Microcontroller

### Step 4.1: Preparing the Pins

The first thing you wanna do is take the 12 pin sticks and put the long pins through from the back of the PCB.

![mcu-pins](https://i.imgur.com/nCc6vAih.jpg)
![mcu-pins](https://i.imgur.com/UwLr58bh.jpg)

Then you want to solder in the pins from the front of the PCB and the clipping the pins, similar to how you did the diode legs. 

![mcu-pins-soldered](https://i.imgur.com/8XYSzoIh.jpg)

### Step 4.2: Preparing the Board

***Note: If you're using hotswap sockets for your MCU, you can go straight to step 4.3***

Because of the location of the switches in the top right corner, you not want to partially assemble the board. So this is the point where you want to preparing your stabilizers and putting them in to place.

![stabilizers](https://i.imgur.com/9IHWrRqh.jpg)

You then want to insert a couple of anchor switches into the plate, including the two switches in the top left corner.

![anchor-switches](https://i.imgur.com/44LAnvkh.jpg)

Then you want to solder in the switches in the top left corner, as these will be hidden by the MCU when it's been soldered in place.

![corner-switches](https://i.imgur.com/1hlOw2Th.jpg)

### Step 4.3: Soldering in the Microcontroller

Next, you want to place the MCU on the pins from the back of the PCB with the components facing away from the boards (The B5 slot should be to the bottom left corner, but make sure to match the silkscreen on the PCB).

![mcu-soldered](https://i.imgur.com/vsIf4G0h.jpg)

***Note: If you're using the hotswap sockets, place the pins into the sockes, put your MCU in place and solder it to the pins. Now you're able to simply remove it from the sockets without having to desolder.***

## Step 5: Testing the PCB

Just to be sure and not having to desolder all the switches again, you want to just do a last test of the PCB to ensure it's all OK. With your MCU in place, plug a USB cable and close the connection of every switch socket on the board. These should trigger the same response as in step 1.2.

## Step 6: Finishing up the build

### Step: 6.1: Soldering in the Switches

Next, you wanna put in all the switches in your preferred layout. Make sure that the bottom row is correct before soldering, to ensure that your keycaps won't be overlapping. You can do this simply by putting the keycaps on the switches to make sure they're in the right locations.

Then simply solder in all of the switches, the same way you did with the diodes. It's all through hole, so the method is the same.

### Step 6.2: Assemblying the Board

Lastly, we just need to assemble the boards. There are two different type of standoffs, used for this board. Three shorter ones and 10 longer ones, all screws are the same. Start off by screwing the three short ones to the bottom plate. This is reversible, so pick the side you like the most. Then screw the feet plate to the other end of the standoffs. This is optional, but gives the board an angle. It you want to have 0 degree angle, you can do that too if you wish. You now have the bottom plate ready. You then want to screw all of the 10 longer standoffs to the bottom plate, on the opposite side of the feet. Then simply place the the finished PCB and plate on top of the standoffs, and screw it down aswell. Apply the rubber bumpons to the corner of the board, and you have finished your keyboard build. Apply the set of keycaps of your choice.

![front](https://i.imgur.com/nBonUObh.jpg)
![back](https://i.imgur.com/wTEznH8h.jpg)

If you have any questions, do not hesitate to get in touch, over on the [Nyhxis Discord](http://discord.nyhxis.com/)

Hope you will be as happy with the keyboard as I have.

Thank you so much for the support.