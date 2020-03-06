# BDN9 Acrylic case
_A simple, versatile acrylic case for Keebio's BDN9._

![BDN9](https://i.imgur.com/pai9M0m.jpg)

Get your own BDN9 kit at [Keeb.io](https://keeb.io/collections/keyboard-pcbs/products/bdn9-3x3-9-key-macropad-rotary-encoder-support?variant=15959960944734). Thank you as well for the [original case files](https://github.com/keebio/BDN9-case).

I set out to make a simple acrylic case when I first built my BDN9. It has been a great design project for me and after a lot of questions and a couple of revisions, I can finally make it available for others to make their own.

**Download ready-to-upload [Ponoko](https://www.ponoko.com/) SVGs from [Releases](/releases/latest), but always verify the dimensions listed in the Ponoko Previewer when ordering.**

## About the Case

The case can be built in 2 case styles, Lo-Pro and Hi-Pro. There are also 2 options for RGB Underglow lighting if you choose to use it, RGB Diffuser or Bottom.

- **Lo-Pro**: A low-profile case look with exposed switches. Will be cheaper and easiest to make, as it requires the fewest acrylic layers, and you could add on a Hi-Pro lip, 12mm M2 screws, and 3mm standoffs later.
- **Hi-Pro**: A high-profile style that uses the same base as the Lo-Pro, and adds layers on top to cover the switches. Requires longer M2 screws (12mm for 2 lip layers, 15mm for 3 lip layers) than what is included in the BDN9 kit.

## Components Needed

- BDN9 Kit and Components: Follow the [BDN9 Build Guide](https://docs.keeb.io/bdn9-build-guide/), but you will not be using the plates and standoffs.
- 4x Standoffs
  - [9mm M2 standoffs](https://www.aliexpress.com/item/32968906213.html?spm=a2g0s.9042311.0.0.49014c4dnATcyT) **OR** 12mm Standoffs (Included in BDN9 Kit). You can use the 12mm standoffs, just add one of the Mid Layer pieces. I just find the height to be too high for my liking.
- 4x Top Screws
  - [12mm M2 screws](https://www.mcmaster.com/92000A019) for a Hi-Pro lip with 2 layers that comes to just below the top of the switch housing.
  - [15mm M2 screws](https://www.mcmaster.com/95836A115) for a Hi-Pro lip with 3 layers that comes to covers the keyswitch completely as well as the bottom of the keycap.
  - Original 6mm M2 screws included in the kit can be used for Lo-Pro case style.
- 4x Bottom Screws
  - Use original 6mm M2 screws included in the kit.

## Acrylic Layers

This case was designed with **3mm thick acrylic layers**, as this is usually easy to find in many different colors. I recommend using [Ponoko](https://www.ponoko.com/) to cut the pieces. No matter your case style, you will need at the very least the pieces for the Lo-Pro style. The layers are arranged here from top to bottom in terms of stacking order. Optional plates are noted below.

Dimensions of ***EVERY LAYER*** should be **73.131mm x 73.131mm**. If using Ponoko, make sure length and height are equal to 73.1mm. If not, simply edit the fields.

### Hi-Pro
Add as many **bdn9\_H1\_lip** layers as you want to create the High Profile lip. I found **2** to be the sweet spot, with 3 being higher but can interfere when using some knobs and keycaps.

### Lo-Pro/Base

1. MX Plate (**bdn9\_L1\_plate**): The thicker 3mm acrylic plate is needed for the sizing of the other layers with the cutout.
2. PCB Plate (**bdn9\_L2\_pcb\_mid**): This plate has one side thinner to allow clearance of the PCB.
3. Cutout (**bdn9\_L3\_cutout**): Has space cutout for USB port (Pro Micro, Elite-C, Proton-C all work) as well as the reset switch.
4. Cutout (**bdn9\_L4\_cutout**): Same as *L3\_cutout*, and is recommended for NO RGB or Bottom RGB.
   1. *Optional* RGB Diffuser (**bdn9\_L4\_diffuser**): If instead you want an RGB Diffuser, then use *L4\_diffuser* instead of *L4\_cutout*.
5. Bottom Plate (**bdn9\_L5\_bottom**): Bottom plate. I recommend Clear Matte (Frosted) or Clear for an RGB Bottom.

### Optional Layers

1. **bdn9\_O\_L5\_full\_mid**: If you cannot find 9mm standoffs, you can use the 12mm standoffs included with the kit and use this piece as a spacer. It is just a single solid acrylic piece with the standoff holes cutout, or add another *bdn9\_L4\_cutout* layer.


## Examples

### Hi-Pro Case, RGB Diffuser, 2 Layer Lip
![Hi-Pro](https://i.imgur.com/mtQvlCx.jpg)
Layers would be:

1. bdn9\_H1\_lip
2. bdn9\_H1\_lip
3. bdn9\_L1\_plate
4. bdn9\_L2\_pcb\_mid
5. bdn9\_L3\_cutout
6. bdn9\_L4\_diffuser (Clear Matte acrylic)
7. bdn9\_L5\_bottom

### Lo-Pro Case, RGB Bottom
![Lo-Pro](https://i.imgur.com/1Mkt1mv.jpg)
Layers would be:

1. bdn9\_L1\_plate
2. bdn9\_L2\_pcb\_mid
3. bdn9\_L3\_cutout
4. bdn9\_L4\_cutout
5. bdn9\_L5\_bottom (Clear Matte acrylic)

### Hi-Pro Case, All Clear Matte, 3 Layer Lip
![Lo-Pro](https://i.imgur.com/d4zhlW3.jpg)
Layers would be:

1. bdn9\_H1\_lip
2. bdn9\_H1\_lip
3. bdn9\_H1\_lip
4. bdn9\_L1\_plate
5. bdn9\_L2\_pcb\_mid
6. bdn9\_L3\_cutout
7. bdn9\_L4\_cutout
8. bdn9\_L5\_bottom
