## GRIN RC Assembly Instructions

## Introduction

Thank you for purchasing the GRIN RC. This kit requires soldering and firmware writing. Please follow the instructions below to assemble it.

## Precautions

This product is compatible with Kailh Choc switches. Keycaps must be 17.5x16.5mm or smaller; MBK Choc is recommended.

## Work Contents

[1. Preparation](#%EF%BC%91%E4%BA%8B%E5%89%8D%E6%BA%96%E5%82%99)  
[2. Confirmation of kit contents](#%EF%BC%92%E3%82%AD%E3%83%83%E3%83%88%E5%86%85%E5%AE%B9%E3%81%AE%E7%A2%BA%E8%AA%8D)  
[3. initial operation check](#%EF%BC%93%E5%88%9D%E6%9C%9F%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D)  
[4. soldering of electronic components](#%EF%BC%94%E9%9B%BB%E5%AD%90%E9%83%A8%E5%93%81%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[5. Soldering of OLED](#%EF%BC%95oled%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[6. soldering of RGBLEDs](#%EF%BC%96rgbled%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[7. Soldering the switch socket](#%EF%BC%97%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%82%BD%E3%82%B1%E3%83%83%E3%83%88%E3%81%AE%E3%81%AF%E3%82%93%E3%81%A0%E4%BB%98%E3%81%91)  
[8. Adjustment of touch sensor](#%EF%BC%98%E3%82%BF%E3%83%83%E3%83%81%E3%82%BB%E3%83%B3%E3%82%B5%E3%83%BC%E3%81%AE%E8%AA%BF%E6%95%B4)
[9. Bottom plate installation](#%EF%BC%99%E3%83%9C%E3%83%88%E3%83%A0%E3%83%97%E3%83%AC%E3%83%BC%E3%83%88%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[10. Switch Plate/Switch Installation](#%EF%BC%91%EF%BC%90%E3%82%B9%E3%82%A4%E3%83%83%E3%83%81%E3%83%97%E3%83%AC%E3%83%BC %E3%83%88%E3%82%B9%E3%82%A4%E3%83%83%81%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[11. Installation of display cover](#%EF%BC%91%EF%BC%91%E3%83%87%E3%82%A3%E3%82%B9%E3%83%97%E3%83%AC%E3%82%A4%E3%82%AB%E3 83%90%E3%83%BC%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91)  
[12. Firmware writing](#%EF%BC%91%EF%BC%92%E3%83%95%E3%82%A1%E3%83%BC%E3%83%A0%E3%82%A6%E3%82%A7%E3%82%A2%E3%81 %AE%E6%9B%B8%E3%81%8D%E8%BE%BC%E3%81%BF)  
[13. Operation check](#%EF%BC%91%EF%BC%93%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D)  

## 1. Preparation

### Prepare necessary parts other than the kit.

![key arrangement](https://user-images.githubusercontent.com/3132296/184517997-46335e94-6a34-457d-919d-be060dce6e9e.png)
- Choc V1 compatible keycaps 17.5x16.5mm or smaller
- 66 Kailh Choc switches

### Prepare tools
- Soldering iron (for electronic circuit boards)
- Solder
- Flux
- Flux cleaner (alcohol or solvent such as IPA can be substituted)
- Tweezers
- Nippers (slightly larger to cut the legs of the OLED)
- Phillips screwdriver (No. 0)
- Rags, Kim wipes, cotton swabs
- Grease, oil (for lubricating stabilizer and switches)
- Tester (to investigate the cause of trouble)

## 2. Confirmation of kit contents
Check that the following items are included in the kit.
If any of the items are missing, please send us a message using the mail icon at the bottom of the top page of the store website.

### Bag (1)
* Substrate
* Switch plate
* Bottom plate

### Bag② * PCB * Switch Plate * Bottom Plate
* 0603 Chip resistor 2.2k 1 pcs.
* 0603 Chip resistor 10k 1 pcs.
* 0603 Chip capacitor 30pF 8 pcs.
* 0603 Chip capacitor 20pF 1 pc.
* 0603 Chip capacitor 100nF 2 pcs.
* 2 touch sensor ICs

### Bag (3)
* OLED module

OLED module ### Bag ④ * 66 RGBLEDs
* RGBLED 66 pcs.
* Switch socket 66 pcs.

### Bag ⑤ * Low head screw short M2x2.5mm 6 pcs.
* Low head screw short M2x2.5mm 6 pcs.
* Low head screw long M2x8mm 3 pcs.
* Spacer for both female screws M2x3mm 7 pcs.
* M2x5mm double female screw spacer 1 pc.

### Bag ⑥
* M2 washer black 4 pcs.
* Low head screw middle M2x5mm 4 pcs.
* M2 screw spacer M2x5mm 3 pcs.
* M2 precision screw M2x4mm 3 pcs.
* Display cover (acrylic plate)
* Rubber feet

## 3. Initial operation check

Remove the board from the bag ①.  
The firmware for operation check has already been written on the board as shipped. First, confirm that it works properly.  

#### Connect to PC and confirm that it is recognized.
#### Short-circuit the terminals with tweezers, etc., and confirm that input is received.
Short-circuit the two points in the picture with tweezers or other conductors and confirm that "1" is input. If the "1" is not entered, please send us a message using the mail icon at the bottom of the top page of the store site.

## 4. Soldering of electronic components

### Install the components in the following order.
* R1: 0603 chip resistor 2.2kΩ
* R8: 0603 chip resistor 10kΩ
* C15～C22: 0603 chip capacitor 30pF
* C23: Trimmer capacitor 20pF
* C24, C25: 0603 chip capacitor 100nF
* U5, U6: Touch sensor IC

### Soldering of chip components

Apply flux and then pre-solder to one of the pads.  
<img src="https://user-images.githubusercontent.com/3132296/184535738-2d754ac4-0466-409e-b996-f62616462318.jpg" width="25%">  
While warming up the pad with an iron, fix the component with tweezers for temporary soldering.  
<img src="https://user-images.githubusercontent.com/3132296/184535757-cba9bc4b-cfa4-48cb-b1e3-fbe4d7df799b.jpg" width="25%">  
Solder the other side of the pattern and then cleanly solder the temporarily soldered side.  
<img src="https://user-images.githubusercontent.com/3132296/184535764-0454520a-ad06-4bf6-b21c-ffa48c4da335.jpg" width="25%">  
Remove the flux.  
<img src="https://user-images.githubusercontent.com/3132296/184535770-6dbacd05-e6ca-49a3-b7ca-29e98304d01c.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184535774-8ed4108c-405f-4446-87cc-94a1390d7b66.jpg" width="25%">  

### Soldering trimmer capacitors

Solder in the orientation according to the silk.  
<img src="https://user-images.githubusercontent.com/3132296/184582545-ad02b40f-f5ad-4f4f-bbea-aad645dbeab0.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184582561-86ccb1e2-e8df-4c02-900d-ec44eb890441.jpg" width="25%">  

### Soldering IC components

Pre-solder one pad on the kadai.  
<img src="https://user-images.githubusercontent.com/3132296/184561582-306fe682-8e2d-43ca-8b99-23c0f8856373.jpg" width="25%">  
Temporarily solder the component by holding it with tweezers while warming the pad with an iron.  
````
Caution
IC components have orientation! Use the silk line markers and the IC's potch to align the orientation.
````
<img src="https://user-images.githubusercontent.com/3132296/184566023-e8063e86-b14c-4699-9d6a-394cc4821440.jpg" width="25%">  
Solder to the other leg.  
<img src="https://user-images.githubusercontent.com/3132296/184561634-93ea5f32-274f-4d13-8f81-7fd14d523529.jpg" width="25%">  
Remove flux.  
<img src="https://user-images.githubusercontent.com/3132296/184561660-ad2d7693-f5e3-45f5-899e-d777de74e72f.jpg" width="25%">  

## 5. Soldering of OLED

Remove the OLED from the bag (3) and solder it.  
Before installation, check that the yellow tape is attached to the connector. If it is peeled off, insulate it by applying cellophane tape, etc.  
<img src="https://user-images.githubusercontent.com/3132296/184564560-0312b95a-ce82-48d5-9333-46bf7f7f98fb.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184563860-c64b7062-c393-49ea-8d0d-c242a7aab497.jpg" width="25%">  

Cut off the legs on the back side with nippers.  
<img src="https://user-images.githubusercontent.com/3132296/184563870-56463e8f-26a6-4ba6-9849-d4e471471e3b.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184563874-a1ba4da2-2d5c-40ec-8a96-85fd644c42a3.jpg" width="25%">  

````
One point.
The legs of the OLED are hard, so use large nippers.
Also, use masking tape to hold the legs in place beforehand to prevent them from flying apart.
````

## 6. Soldering the RGBLEDs

````
If the LEDs do not light up after soldering, try rewriting the firmware to the following test firmware first.
https://github.com/policium/grin_rc/tree/main/firmware
````

Solder the RGBLEDs in order of decreasing number. Also, be careful that the direction of the LEDs is different for each line.  
Remove the RGBLED from the bag (4) and insert the RGBLED into the hole while aligning the triangular marker with the notch in the foot of the RGBLED.  
<img src="https://user-images.githubusercontent.com/3132296/184566091-fd26ca73-329e-4cd8-9d70-92109d34ba1f.jpg" width="25%">  

Apply flux before soldering; do not overheat the RGBLED for a long time as it is sensitive to heat.  
<img src="https://user-images.githubusercontent.com/3132296/184561978-fc616f62-c0b6-46b9-bc6b-7c01f51278b3.jpg" width="25%">
<img src="https://user-images.githubusercontent.com/3132296/184561982-893cc023-a365-495e-ad32-d99394312fc1.jpg" width="25%">  

Remove the flux.  
<img src="https://user-images.githubusercontent.com/3132296/184562003-3bc0e751-550e-4e33-9e28-217fe200ed0f.jpg" width="25%">  

Connect to a PC and verify that the LEDs light up; since the RGBLEDs communicate in numerical order, some RGBLEDs may not light up.  
If there is an RGBLED that does not light up, check the RGBLED that does not light up and the RGBLED one before it.  

## 7. Soldering the switch socket

Remove the socket from the bag (4), insert it into the hole and apply flux.  
````
Caution
The socket has an orientation, so insert it carefully according to the silk.
The socket may be damaged if it is inserted in the wrong direction.
````
<img src="https://user-images.githubusercontent.com/3132296/184566942-91ed057b-3136-411e-ac8c-6533ad874014.jpg" width="25%">  

Solder and remove flux.  
````
Caution.
Be careful not to float the socket. This can cause poor contact.
````
<img src="https://user-images.githubusercontent.com/3132296/184567210-c9687893-0d89-4d8a-8be0-f78a6f19f538.jpg" width="25%">  

````
One point
It is easier to solder the socket if you install the switch and switch plate first.
Don't forget to install the stabilizer first!
````

## 8. Adjust the touch sensor

Adjust the sensitivity of the touch sensor. Turning the trimmer capacitor one revolution cycles the sensitivity from high to low.  

Connect to a PC with a text editor open.  

When the touch sensor responds, "TAP" is displayed on the OLED. Turn the trimmer capacitor and rotate it from a state where it responds without doing anything to a point where it stops responding. Rotate another 15 degrees from the point where it stops responding. Touch from above the switch panel to confirm that "TAP" is displayed. If it is out of tune, fine-tune it.  

## 9. Bottom plate installation

Take out 4 pieces each of the low head screw short and both female screw spacers M2x3mm from the bag (⑤) and install them in 4 places.  
![GRIN_RC_bottom_1](https://user-images.githubusercontent.com/3132296/188760339-a5c32d42-2da7-4533-b665-5af4510d60f8.png)

Take out 3 pieces each of low head screw long and both female screw spacers M2x3mm from bag ⑤ and install them in 3 places.  
![GRIN_RC_bottom_2](https://user-images.githubusercontent.com/3132296/188760380-84f08afe-6251-4de5-be64-1ae502353ff0.png)

Take out one low head screw short and one M2x5mm double female screw spacer from bag ⑤ and install them one at a time.  
![GRIN_RC_bottom_3](https://user-images.githubusercontent.com/3132296/188760392-72a24b13-e2ac-40c5-8934-d73009b65aa0.png)

Lay the board on the bottom plate.  

## 10. Switch plate/switch installation

The fit of the switch plate and switch is hard. Install carefully so as not to damage the switch claws and terminals.

Take out three M2x6mm double threaded spacers from the bag (6) and install them.
![GRIN_RC_pcb](https://user-images.githubusercontent.com/3132296/188761709-7392534e-0ecc-44b5-b47a-4761839bc401.png)

Attach the stabilizer to the switch plate. Apply grease beforehand if necessary.  
Here is a view from the back.  
<img src="https://user-images.githubusercontent.com/3132296/184582858-4af13b18-ccd3-404b-a1b1-adef978634f5.jpg" width="25%">  

Attach some switches to the switch plate first.  

Lay the switch plate on top of the board. Be careful not to bend the switch terminals.  

Take four medium low head screws and four black M2 washers from bag ⑥ and install them in four places while inserting the black M2 washers between the board and the switch plate.  
![GRIN_RC_top_1](https://user-images.githubusercontent.com/3132296/188760863-b3fa8d52-41c2-4f89-86fc-ff132f58ff5d.png)

Take out one low head screw short from bag ⑤ and install it in one place.  
![GRIN_RC_top_2](https://user-images.githubusercontent.com/3132296/188761060-ef044fed-29c2-47a9-b4c3-6d23ac066c75.png)

Install the switch.  

Stack the switches on top of each other, taking care to avoid the switch terminals.  

Push it in with tweezers while holding down the nails. (Since it is hard, the claws may bend if you push it in only by hand.)  

## 11. Attach the display cover

Remove the display cover from the bag (6) and remove the protective paper.

Take out three M2 precision screws from the bag (6) and attach the display cover.

## 12. Writing the firmware

Download the firmware from [here](https://github.com/policium/grin_rc/tree/main/firmware) and write the firmware.
The standard firmware is "grin_keebs_grin_rc_default.zip".
Use QMK Toolbox to write the firmware.
Press and hold the tact switch to enter DFU mode.

## 13. Operation check

When the writing of firmware is completed, it can be used as a keyboard. Check that all switches are entered, and modify them if necessary.  
That's all for now. Thank you for your hard work.
