# Designs
The purpose of Handybox is to benefit several types of projects with one standard part, accompanied by several other standards that have a well-established ecosystem and many available components near you at brick-and-mortar stores.
I Hope you benefit from the concepts here - even without building any handybox designs you will find some techniques that save time in CAD, prototyping, wiring, or creating new concepts for designs.

## Large Box
The large box is uploaded as a "configuration" of the solidworks model, in grabCAD.  It's a square box, sometimes sold with 4 tabs for 2-gang configuration.  These are available between $3 to $4 in North American hardware stores, usually are 1.5 inches in depth and have commonized holes (called 1/2 inch or 3/4inch trade size) with the other deep-drawn handybox designs.  It's a thick steel around 1.7mm, galvanized for mild rust protection and plenty sturdy for enclosing mechanical 3D printed assemblies.
* Download [Square Box CAD Model](https://grabcad.com/library/squarebox-1) on grabCAD, 2026, or 
* Download [2-Gang Handybox Model on grabCAD](https://grabcad.com/library/openbox-1) and open the square box configuration

-![cad model image, linked 1](https://grabcad.com/screenshots/pics/37a5e82dfe3955bec16e30c24299a862/original.JPG)
-![cad model image, linked 2](https://grabcad.com/screenshots/pics/e7731aa98c01e3f9e556b7b687b6b94e/original.JPG)
-![cad model image, linked 3](https://grabcad.com/screenshots/pics/fe16a97670b58916f904fab01d5207ad/original.JPG)

## DIN Mount
Mount your boxes to your DIN rail, multiple orientations & box sizes. This bracket is parametric, with configurations shown in the animated GIF. The narrow option has 1-in spacing for the 1-gang box and the wide option matches the 1.5in spacing of the square boxes found in local stores.
* Download [DIN mount bracket on GrabCAD](https://grabcad.com/library/handymount-1)

- ![cad model DIN mount assembly](https://grabcad.com/screenshots/pics/6cb35d3681daa2a8277679868fdc6afa/original.jpg)
- ![din mount in use, photo](https://grabcad.com/screenshots/pics/172e093a41ca89a2b01bc5f8ab06374a/original.jpg)
- ![din mount in-use, backside photo](https://grabcad.com/screenshots/pics/c397021bfe7a303dc420d1edc8d0b6a9/original.jpg)

## Bushing
This bushing design fits the standard 1/2inch knockout and creates a port for a variety of connectors. A feature for electrical and mechanical functions. Version 1 is adapted for fixing anderson connectors into the wall of a panel. It can be adjusted for different hole sizes, or different center features.  You may wish to use it as a grommet, or adapter for a 10mm pushbutton, or 100 other items.  The idea is that a new user gains a new function but retains the investment of the code behind the nicely made parametric part.  The feature tree is easy to navigate, so you may update the design without knowledge of all the original design considerations. (just like open source software).
* Download [Bushing CAD model on grabCAD](https://grabcad.com/library/ebushing-1)
  
- ![img handybox large](https://github.com/user-attachments/assets/0e74d687-8dab-4486-bea9-78ceadb83627)
- ![img handyMount image](https://github.com/user-attachments/assets/920e28c6-80b8-4301-968d-de2845a30da9)
- ![img_eBushing1](https://github.com/user-attachments/assets/84268de3-2954-4cb2-bd8d-b86bb7608e46)

## Reducer
This design allows for your choice of machine screw to fasten into the large 22mm holes in the plate steel.  The STEP model features an M6 fastener size with hex nut. But if you access the SOLIDWORKS model you can easily modify it for any size.  The post includes one variation as an example of how to pivot the design for new shapes.  It's designed for a thicker steel with a shorter hoop and a larger M8 bolt. 

- ![img reducer assembly sectioned](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/91eedccf81eb2700d3b21cf090a410d0/original.jpg)
- ![img reducer assembly 2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/bf1a57fef2f3299b50b64ec13ba34092/original.jpg)
- ![img reducer variation](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/18ac54326f80196494b9087c708e375e/original.jpg)

The next photos show the reducer used in assembly.  (left) you can pass a 6mm shaft through the reducer and it fits concentric with the original box holes. (right) with a screw and nuts clamping on the reducer, it is ready to withstand additional jobs like an axial load.

- ![img reducer shaft](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/7ddc9cd247eba798792123a01b9c7df0/original.jpg)
- ![img perpendicularity](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/db0eed128355d71af3a27b6074d867ea/original.jpg)
- ![img load bearing](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/220be329b34217bfc16bc8b06a401091/original.jpg)

## Bearing Hub

(2026) Hub_M6 is a new version derived from Hub0 and Hub1.  This module fits a size 606 bearing and clamps to the box with M6 fasteners and nuts (previous version uses M5).  It requires the holes of the box to be slightly enlarged to correct for the deformation in the hole pattern from the stamping process.  The handybox holes are reamed to 7.0mm and gently chamfered for deburring.

_see images of the hub M6 CAD model below_
- ![hub_m6 photo](img/hubM6_1.jpg)
- ![hub_m6 photo](img/hubM6_2.jpg)
- ![hub_m6 photo](img/hubM6_3.jpg)

_see photos of the hub M6 and its implementation below_
- ![hub_m6 photo with M6 nut spec](img/photo_hubm6_1.jpg)
- ![hub_m6 photo installed on handybox](img/photo_hubm6_2.jpg)
- ![hub_m6 photo with bearing spec](img/photo_hubm6_3.jpg)
- ![hub_m6 photo, box interior](img/photo_hubm6_4.jpg)
- ![hub_m6 photo, holes alignment](img/photo_hubm6_5.jpg)
- ![placeholder](img/placeholder.jpg)


(2025) Hub0 and Hub1 are published. The hub fastens a bearing to the handybox floor, and this design features the octagon shaped box.  All of the large boxes (square and octagon) feature a standard set of holes at the floor which are ready to mount a feature like this.  Use this hub to pass a shaft through the center of the box for a symmetric rotating assembly.
* [get the hub model here](https://grabcad.com/library/hub_0-1])

- ![hub photo, assembly](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/1a4d9a8ec5c7cb4b650467375a733be5/original.jpg)
- ![hub CAD image, assembly](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/20a22f48b02a1b4dba5f0afc02ead7f7/original.JPG)
- ![hub with bearing, photo](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/17ec3cad3c77350a9c5131e5d68c04a2/original.jpg)



## Covers
One model for many purposes.  This model branches into letters A through G so far (2025.10) but I skipped a few that are less common needs.  I produced images for most variants to date.
* cover B fits the small shaft found in all the dremel tools and 1/8 inch rotary devices, an extremely common shank size.
* cover E gives a flat surface sectioned into smaller areas for enhanced printing without warping, in ABS.
* cover E has a second variety with sockets, but it resides in the same .sldprt model as a configuration.
* cover F features hex-shaped holes for insertion of hex driver bits.  The main configuration has a hole depth for the ever-common 1 or 2 inch height of these bits.
* cover J is for holding an instrument panel and features a raised boss, which effectively adds volume to the box.  This particular design fits a DC motor driver and it's expected that many users will have rectangles, for which you can adjust the size with a couple of dimensions.
  
- ![cover B](img/img_coverB1.jpg)
- ![cover b 2](img/img_coverB2.jpg)
- ![cover e topside](img/img_coverE.jpg)
- ![cover e underside](img/img_coverE_flat.jpg)
- ![cover e sockets version](img/img_coverE_sockets.jpg)
- ![cover f for hex](img/img_coverF.jpg)
- ![cover f2](img/img_coverF2.jpg)
- ![cover f3 section](img/img_coverF3.jpg)
- ![cover J for panel insert](img/img_coverJ1.jpg)
- ![cover J for panel insert](img/img_coverJ1.jpg)


## Octagon Box
This variety is modeled after Raco part number 8125, having octagon shape and holes for both 1/2 and 3/4inch conduit, the most common steel conduit sizes.  I made a very clean model in Solidworks for open sourcing.  This abstacts some details and gives the overall shape which is reliable enough to design mating parts.
* Grab CAD for [octagon box](https://grabcad.com/library/octagonbox-1)

_Photos below show the plain octagon box, and integration of a bearing hub.  The hub model is also posted on grabCAD and fits a common 608 bearing with 8mm ID._ 
* ![linked image octagon box1](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/c9c166a4ac475c26c91e5991418ce1ca/original.JPG)
* ![linked image octagon box2](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/5c05e83e79c97dc53cca70ca8001ef05/original.JPG)
* ![linked image octagon box3](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/9366ce5543546b635158687a36a0c62e/original.jpg)

## DC Socket Adapter
To be populated as I create videos to explain features.

**Car Adapter**
This video gives a full tutorial on building the car adapter design which is a combination of many design methods that are reproducible for 10,000 applications.  It discusses the efficiency benefits of the dc adapters, 3d printed interfaces with tolerances and parametric design elements, and much more. 
<iframe width="703" src="https://www.youtube.com/embed/VLrEtrU10ow" title="Build a DIY power supply for powering electronics - using openBox" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

See photos below for a clear image of the "car adapter" design using the handybox, 18v power tool battery, silicone wires, and other favorite versatile supplies.

- ![car adapter, anderson](img/img_carAdapter1.jpg)
- ![car adapter, socket](img/img_carAdapter2.jpg)
- ![car adapter, with battery module](img/img_carAdapter3.jpg)

## Liner

Easily adjust the box volume with a liner. This addition is made of a foam pad and I call it a "floor liner" and use it to control the height of racked items or protect parts from scatching at the floor of the box. For items standing in the box used as a rack, we can adjust heights without any 3D printing changes.  Alternately, we may want to line the base to prevent contact between brittle metal and the box floor.  This can be achieved in two minutes with some foam or other lining material.  For my example, I wanted to offset the floor for all of the 3rd row taps, due to their short length of shank, they could fall down and become hard to grab.  As needed, just slice a piece of foam or add more layers to offset the height of a row of bits.  Also, this keeps bits from chipping if they drop against the steel box.

![box floor liner image](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/71db1b41ccb4b189cb514e836513f97c/original.jpg) 
