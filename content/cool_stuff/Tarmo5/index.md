---
title: "Bulit a Tarmo5"
subtitle: "3D Printed RC Car from EngineeringNS"
summary: "3D Printed RC Car from EngineeringNS"
date: 2024-01-13
cardimage: card_Tarmo5.jpeg
# featureimage: photo1.jpeg
caption: Image caption
# authors:
#   - Christian: author.jpeg
---
A GoPro shot from top of my Tarmo5! Of course ended with the left steering link broken :boom:
{{< youtube id="n7oqzd1Z32c" title="20240317 Tarmo5 UMich BBB Test Drive" autoplay="false" >}}

Tarmo5 is a 3D printed RC car created by [EngineeringNS](https://www.reddit.com/r/EngineeringNS/). The model files are everywhere, and the 3D printing, RC car community have shown substantial love to this design. Tarmo5 is already well documented, but there are still lots of little things that weren't mentioned or shown in the guide. Things like soldering, remote control, wiring, ..., it requires prior knowledge from RC car community to fully build the car. 

{{< figArray subfolder="images" figCaption="Parts, cool BBB lobby shot, and have built car" numCols="3" >}}




# My Build Notes
Below are the notes I took when I was building the RC car. I also tried to comment on the youtube video part by part, but here is the whole text.
My list of parts to use to pair with the video build guide from EngineeringNS \
Some useful links:
- https://www.youtube.com/watch?v=cUGfVkaP9bc&list=PLaiGNg1YBwrozUtk9eJII2MJNWrulZJaS&index=1
- https://drive.google.com/file/d/1ZsQY1Mrz17x6WVSmiWJ7Bx5Mh-WtjloM/view

## Part1: 2x rear wheel 
- 3D parts:
    - C01 (make sure you use C01 instead of C02, they look really similar)
    - C03
    - C04
- non 3D parts:
    - 4x 6mm steel balls
    - 1x M4x35mm hex head bolts

##  Part1.5: 2x rear gear housing thingy, same as part1 but without the bolt, will use this in part4 
- 3D parts:
    - C02
    - C03
    - C04
- non 3D parts:
    - 4x 6mm steel balls

##  Part2: 2x rear wheel
DVS: 2x Missing M4 washer \
DVS: 2x C10 need to print? but size is wrong! I think it doesnot matter, have to reprint!
- 3D parts:
    - A03
    - part1
    - C10 (yeah need total 4x C10 instead of 2x, one for each wheel)
- non 3D parts:
    - 2x 15x24x5mm bearing
    - 1x M4 nylon nut
    - 1x M4 washer (not in BOM, need 4 in total)
    - 1x 100mm OD wheel


## Part3: rear plate assembly
DVS: 4x M4x45mm socket head screw? (instead of 40mm)
- 3D parts:
    - B13-T
    - 4x A02
- non 3D parts:
    - 4x M4x40mm socket head screw
    (other comment suggests 45mm, I used 40mm but would prefer 45mm as well)

## Part4: gear box assembly
- 3D parts:
    - B02
    - C07
    - C06
    - 2x C05-T
    - 2x part1.5
- non 3D parts:
    - 2x M3 threaded rod 350mm
    - 2x M3 nylon nut
    - 2x 15x24x5mm bearing
    - 3x M4x20mm socket head screw

Make sure the M3 nylon nut is about that deep into the thread, otherwise it will stick out in the front and cant mount the front bumper

## Part5&6: gear box assembly cont
- 3D parts:
    - part3
    - part4
    - B12-T
    - A01
- non 3D parts:
    - 3x M4x20mm socket head screw

## Part7: gear box & rear wheel
DVS: 6x M4x45mm socket head screw? (instead of 40mm)
- 3D parts:
    - part5&6
    - part2
    - B01
- non 3D parts:
    - 4x M4x40mm socket head (wheels to A02, I used 40mm but would prefer 45mm with nut)
    - 2x M4x40mm socket head (B01, not sure about 45mm but might be better)

Yes do part 9 first as @MultiHaskar suggest! otherwise hard to screw in the moter mount

## Part8: mount rear shocks, bounce bounce!
- 3D parts:
    - part7
- non 3D parts:
    - 2x 80mm shock
    - 4x M3x16mm socket head screw

##  Part9: motor
DVS: 2x M4x45mm socket head screw? (instead of 40mm)
- 3D parts:
    - part8
    - B09
    - C08
- non 3D parts:
    - 4x M3x8mm socket head screws (mount motor to B09)
    - 1x coupling insert and the two small thread thingy
        (this is the drill bit depth stop, 5mm ID 1mm OD shank)
    - 1x 15x24x5mm bearing
    - 2x M4x40mm socket head (mine holds but would prefer 45mm)

Also mine D3542 brushless motor does not have a flat spot, the drill bit depth stop still bites on to it though

## Part10: body
- 3D parts:
    - part9
    - B03
- non 3D parts:
    - 1x super lube

## Part11: 2x front wheel
DVS: 2x Missing M4 washer
- 3D parts:
    - A05/A06(right wheel/left wheel)
    - C09
    - C10
- non 3D parts:
    - 1x M4x35mm hex head bolts
    - 2x 15x24x5mm bearing
    - 1x 100mm OD wheel
    - 1x M4 nylon nut
    - 1x M4 washer (not in BOM washer here again)

## Part12: front plate assembly
- 3D parts:
    - B10-T
    - B11-T
    - 4x A02
    - A01
    - B05
- non 3D parts:
    - 5x M4x20mm socket head screw
        - 2x B10-T to B01
        - 3x A01 to B01
    - 4x M4x40mm socket head screw (would prefer 45mm)

This is viewing from the front of the car, so the left side of the video is the front right wheel, and the right side is the front left wheel

## Part13: front plate assembly cont, mount shocks, bounce bounce!
- 3D parts:
    - part11
    - part12
    - 2x A04
- non 3D parts:
    - 2x M4x40mm socket head screw (to mount A04 to A05/A06)
    - 4x M4x40mm socket head screw (to mount A05/A06 to the A02s, would prefer 45mm)
    - 4x M3x16mm socket head screw (to mount the shocks)

as @DSdvdDS suggests, should connect everything (ESC, motor, servo, receiver [X6FG], battery, remote control) and test the electric side works first before putting everything together

## Part14: steering servo
- 3D parts:
    - B04
    - A09
    - 2x A10
    - A07 (2:22 to front right wheel)
    - A08 (2:53 to front left wheel)
- non 3D parts:
    - 1x servo
    - 4x M3x16mm socket head screw (to mount the servo) (but M3x12mm also works?)
    - 1x M3x8mm socket head screw (servo arm to A09)
    - 1x M3 nut                   (servo arm to A09)
        I put a M3 nut between the servo arm and A09
        cuz not sure why A09 bends when connecting to A07 and A08
        Maybe the servo I use has different dimensions?
    - 4x M4x12mm socket head screw (to mount A07, A08 to B04)
    - 2x M4x20mm socket head screw (to mount A07, A08 to A09)
    - 2x M4x20mm socket head screw (to mount A07, A08 to A10)
    - 2x M4 nut

## Part15: front part to body
- 3D parts:
    - part10
    - part12
    - part14
    - B06
    - B07-T
- non 3D parts:
    - 2x M3 nylon nut
    - 5x M4x20mm socket head screw (mount B07-T to B06)
    - 2x M4x20mm socket head screw (mount A10 [steering link] to wheels)

The ESC needs some soldering work! or at least mine comes with bare wire, the red and black wire needs to solder to a Dean's T male connector to connect to the lipo battery, and the yellow, blue, orange wires need to solder to a 3mm female jack. These parts are not mentioned in the BOM

Also should do the whole ESC/receiver/transmitter calibration thingy before mounting everything in place, otherwise its hard to do so once its on there. 

## Part16: mount ESC
- 3D parts:
    - part15
    - ESC
    - B08-T
    - receiver (X6FG)
- non 3D parts:
    - 2x zip tie (or just one, comes with the ESC)
    - 1x M4x20mm socket head screw for the battery clip
    - 1x a small piece of double sideed tape (to tape down rx)

So channel 1 on the receiver X6FG is for steering, so have to connect the servo wires to it. The 3 wires are colored orange (signal), red (power), brown (ground), put the brown one to the edge of the receiver, Channel 2 is for throttle. Connect the 3 wires, white (signal), red (power), black (ground), from the ESC, put black at the edge of the receiver.

For this part, need to charge the battery first. I used the imax B6 in our lab to charge it, here is the guide I followed [this link](https://www.youtube.com/watch?v=MvFv3CBrJVM) to do so. This lipo charger is also not in the BOM.

And this is the guide I followed to calibrate the remote itself: \
https://youtu.be/Sk6yh_Q2O6g?si=ZR5iD-WNL8YShacS&t=242 \
To let the ESC know the controllers throttle range: \
https://youtu.be/vppGnYVdMTE?si=M-0khJUi3vdgDzaA&t=650

## Part17: mount ESC
- 3D parts:
    - part16
    - battery adapter (if using smaller battery 3200mAh, https://www.printables.com/model/387801-tarmo5-battery-adapter/related)
- non 3D parts:
    - 1x battery
    - 1x remote control (dumbo X6)

And vola, car is running!