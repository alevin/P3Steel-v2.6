# P3Steel v2.6
### A new Prusa i3 Steel frame version

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Hi, welcome in the P3Steel v2.6 repository. Here you can find my newly created version of the P3Steel frame. If you think it is the right frame for you, just download it and laser cut it; otherwise please tell me what would you modify in my project, I'll be very interested in your opinion!
# Warning!!!
> I haven't built this frame yet, but I've already sent the cad file to a factory which has a laser cutter: I'll can guarantee that the design is correct __*only*__ when I'll have all the pieces in my hands. If you're interested in assembling this frame, please wait some days before laser cut it.

## Folders
### cad
In this folder you'll find all the ready-to-be-made designs, both in dxf and dwg formats.

### blocks
Here, divided in subfolders, you'll find all the building blocks of the frame so that it's possible to modify one independently from the others.

### img
This folder contains images and photos of the frame.

## Philosophy
_All changes committed to the pre-existent design have been made with the purpose of avoiding non-functional things and of adding elements I felt were missing. Neither optimizing laser cut times nor cutting down material costs was my priority: my only goal was to make a more functional frame, trying to solve old problems which have been affecting the P3Steel project for years. I just wanted **the best Prusa-style frame possible**: the one which has everything it's needed._

_I'm very interested in problems which may have disturbed P3Steel users in these years. Someone may have already tried quick fixing them (for example by making printed parts like the Y-idler made by [toolson](http://www.thingiverse.com/thing:1054909)): it would be much better to try implementing those solutions in a more **structural** way, directly in the printer frame._

## Changes with respect to the [2.5 DXL version by AndrewBCN](http://reprap.org/wiki/P3Steel#Frame_versions):

### **_ADDS_**

1. Two spool holder brackets added with their respective fixing holes;

2. Four elements added to block Y-axis rods (with their respective fixing holes);

3. Two elements added to block Z-axis rods (with their respective fixing holes);

4. Two elements added to reinforce the frame base (with their respective fixing holes);
 
### **_DELETIONS_**

1. Both fixing holes for NEMA17 motors in the lateral panels were eliminated (they both were in rather uncomfortable positions, moreover one of them turned out to be useless because of the mounting position of the power supply which covers it almost completely);

2. Some holes in the front and back base panel were eliminated because of them being too close to the fixing holes previously added (see 4) );

### **_MODIFICATIONS_**

1. I've changed the position of some elements in order to lessen the impact of the already listed adds;

2. I've changed the Y-idler element. I've enlarged it a little just to be able to move the bearing fixing hole. The hole was moved down and forward, then its diameter was reduced to 3.2mm (just like [toolson](http://www.thingiverse.com/thing:1031144) did with his printed parts). This way to assemble the mechanical parts of the printer only M3 screws are needed. It's recommended to use a 20 teeth GT2 pulley with a 3mm bore bearing. Otherwise you can also use the 5mm bore version of the bearing, having firstly drilled the hole up to that diameter.


## Technical enhancements made on the design:

1. All the elements in the design were put in the same (and only) "0" layer;

2. A lot of problems caused by non-correctly closed lines were fixed;

3. Some useless lines were deleted as they were identical and overlayed or lined up together (and for this reason they were substitued by a single longer line);

4. All closed lines were converted into polylines;

5. Every piece was converted to a block which has a sintetized name;

6. Every block was saved in a separate file, allowing it to be modified independently from the rest of the design;

7. The design was saved and exported in the following formats:
    - DXF;
    - DWG;
    - PDF;
    - PNG.
