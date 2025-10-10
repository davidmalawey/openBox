# Design
The purpose of Handybox is to benefit several types of projects with one standard part, accompanied by several other standards that have a well-established ecosystem and many available components near you at brick-and-mortar stores.
I Hope you benefit from the concepts here - even without building any handybox designs you will find some techniques that save time in CAD, prototyping, wiring, or creating new concepts for designs.

# Videos
To be populated as I create videos to explain features.

## Build a Car Adapter

<iframe width="703" src="https://www.youtube.com/embed/VLrEtrU10ow" title="Build a DIY power supply for powering electronics - using openBox" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

# Features
A technical review for specific engineering features, listed by purpose

## Floor Liner

Control the height of racked items or protect your parts. For items standing in the box used as a rack, we can adjust heights without any 3D printing changes.  Alternately, we may want to line the base to prevent contact between brittle metal and the box floor.  This can be achieved in two minutes with some foam or other lining material.  For my example, I wanted to offset the floor for all of the 3rd row taps, due to their short length of shank, they could fall down and become hard to grab.  As needed, just slice a piece of foam or add more layers to offset the height of a row of bits.  Also, this keeps bits from chipping if they drop against the steel box.

![box floor liner image](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/71db1b41ccb4b189cb514e836513f97c/original.jpg) 

# Parts
Components, methods, and considerations for organizing wires in projects.  It's best to watch this before you design, so you can discover parts to integrate in your project plans.

## Main Parts
Main components around which the other parts are designed.

* EMT Conduit
* Handybox electrical boxes with 1/2in knockout holes
* Switches, 22mm, toggle switches
* Outlets, ordinary 120v North America standard

**Large Box**
The large box is uploaded as a "configuration" of the solidworks model, in grabCAD.  It's a square box, sometimes sold with 4 tabs for 2-gang configuration.

**HandyMount**
Mount your boxes to your DIN rail, multiple orientations & box sizes. This bracket is parametric, with configurations shown in the animated GIF. The narrow option has 1-in spacing for the 1-gang box and the wide option matches the 1.5in spacing of the square boxes found in local stores.

**Bushing**
A feature for electrical and for mechanical function

* ![handybox](https://github.com/user-attachments/assets/0e74d687-8dab-4486-bea9-78ceadb83627)
* ![handyMount](https://github.com/user-attachments/assets/920e28c6-80b8-4301-968d-de2845a30da9)
* ![img_eBushing1](https://github.com/user-attachments/assets/84268de3-2954-4cb2-bd8d-b86bb7608e46)


Version 1 is adapted for fixing anderson connectors into the wall of a panel. It can be adjusted for different hole sizes, or different center features.  You may wish to use it as a grommet, or adapter for a 10mm pushbutton, or 100 other items.  The idea is that a new user gains a new function but retains the investment of the code behind the nicely made parametric part.  The feature tree is easy to navigate, so you may update the design without knowledge of all the original design considerations. (just like open source software).

# Benchmarks
Every good design begins with an evaluation stage.  If you want to invent something that helps the community, start by searching for benchmarks. 
* existing products that perform **the function** you want
* existing parts that contain **the geometry** you'll design
* industrial parts that are often more robust than consumer goods
* unrelated market categories which solve equivalent functions

In the benchmarking process for an OpenBox-related design, start with the catalog & technical drawings below.


## Design Catalog

### USA Handy Box Specifications by Brands

#### 666 CUS by RACO (4” x 2” x 1-7/8”)

![666 CUS Manufacturer Image](https://do1jvmih5t6vs.cloudfront.net/userfiles/ad/large/raco_666.jpg)

- 4 in. x 2 in. Handy Box, Drawn, 1-7/8 in. Deep with Seven 1/2 & One 3/4 in. KO's, Raised Ground
- [download (100mb)](https://lobfile.com/file/TMfW62ny.pdf)
- [img_technicalData1](https://github.com/user-attachments/assets/8c5ebed6-eeb9-4228-b587-385ee21200a7) _see material properties, dimensions, & more_
- [image techsheet](img/img_racoData1.jpg 'class=image-25') _technical sheets published by manufacturers_
- [img_drawing](https://github.com/user-attachments/assets/256211c1-f47f-49f2-863e-14f5fdbfc8e6) _dimensional drawings by manufacturers (Raco & more)_

We don't have a specific structure for posting data but as I accumulate useful drawings and reliable documentation behind the branded boxes (suchas Raco by Hubbel) I will upload the content for others to download.  At times, I markup a PDF with mechanical drawings to point out the key items instead of starting a document from scratch.
