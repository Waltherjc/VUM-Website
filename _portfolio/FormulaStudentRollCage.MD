---
title: "Formula Student Roll Cage"
excerpt: "This roll cage was assembled from straight square and circular 1 in. tubing."

header:
  image: assets/img/Bike Full Render.png
  teaser: assets/img/Bike Full Render.png
gallery1:
  - image_path: assets/img/Wire Roll Cage.jpg
gallery2:
  - image_path: assets/img/Roll Cage Welding.jpg
gallery3: 
  - image_path: assets/img/John Walther Roll Cage.jpg
gallery4:
  - image_path: assets/img/Bike Real 1.jpg
  - image_path: assets/img/Bike Real 2.jpg
gallery5: 
 - image_path: assets/img/Bike GIF.gif

   
---
<br>
## Introduction

The goal of this project was to assemble a roll cage for a high school Formula Student car. The roll cage had to meet certain safety standards, as well as accomodating the height of the driver. This roll cage formed the basis for the rest of the Formula Student car that was constructed in later years. <br><br>

The roll cage fabrication first started with CAD modeling using Autodesk Fusion. Then, using thin flexible wire, the roll cage was outlined on the foundation for the roll cage. After the outline was finished, tubing was cut, notched, and bent to fit the parameters, before being MIG welded.


## Design

### CAD Modeling
The basis of the car's roll cage came from another school's CAD design. However, with the base of the roll cage being assembled in a previous year under different parameters, the roll cage design needed to be modified. <br><br>

The main point of modification was adjusting the connection points between tubes to align with the cross-sectional beams that were established in the base. This meant that many of the components were shortened, lengthened, or their curvature was altered to accomodate those changes. <br><br>

After those adjustments were made, the next point of emphasis was the mode of connection between curved and square tubing. Through the cad design, the angle of the tubing had to be documented to ensure proper assembly. The most complex assembly point was a connection of three circular tubes to a square tube. This required multiple iterations to ensure that they all met at a single point to effectively distribute force from the node.


### Wire Prototype

Using the modified CAD design, a wire prototype was assembled on top of the base of the roll cage. This was used to ensure that our measurements used in the CAD design were accurate. To accomplish this, thin, pliable metal wire was cut, bent, and taped into position. By using the wire prototype, it would be much easier to translate to the metal tubing by using the metal wire as a measurement tool when cuting the tubing. 

{% include gallery id="gallery1" %}


## Assembly

Starting with straight 1 inch square and circular tubing, pieces were cut using a chop saw. The size of the pieces that were cut was determined by straightening the wire from the prototype. Once the pieces were cut, they had to be modified to properly fit on the car. To get the desired curve for some of the pieces (only the circular tubing was curved), a tube bender was used. For the pieces that were bent (only the square tubing was bent), the desired angle was cut out of the material before bending the tube to close the gap. Half of the desired angle was measured in each direction radiating outward from one side such that when the gap was closed, the two faces were equal is length, making welding more feasible. Finally, to make the pieces of tubing sit as flushly as possible, air grinders and dremels were used to grind down the ends of the tubes to match the desired angle and shape. <br><br>

{% include gallery id="gallery2" %}

Once the pieces were cut, they were welded to the roll cage. MIG welding was used due to availability and ease. First, all of the pieces were tack welded into position. This allowed fixes to be made if necessary without wasting too much material. Once everything was tack welded into the correct posion, they were covered by full welds to ensure structural integrity.


## Final Model

{% include gallery id="gallery3" %}





### Rotational Mechanism

To rotate the phone, a simple detent mechanism was used. This mechanism uses a small spring-loaded ball bearing that engages with notches in a gear to hold a phone at specified angles. The detent mechanism provides tactile feedback when the phone locks in place while also allowing for easy rotation when enough force is applied.

{% include gallery id="gallery1" %}

The detent mechanism created for this project works very well, especially when harnessing the added weight from a phone. However, one limitation is that it required the phone to be pushed in the direction of the spring before rotating. This could have been solved with a lighter spring or two symmetrical springs. <br><br>

The detent gear was SLS printed from nylon powder for ultimate durability. The only modification that was made to the part due to the potential of part growth with SLS printing was increasing the diameter of the hole to allow the M5 bolt to rotate with ease. <br><br>


### Phone Holder

The goal with the phone holder was to secure a phone at its corners such that the securement mechanism wouldn’t interfere with what is being displayed on the phone. To accomplish this, existing Amazon products were researched, and one [promising design](https://www.amazon.com/Bike-Tie-Connect-Kit-Universal/dp/B0BNBLCWL2/ref=sxin_17_pa_sp_search_thematic_sspa?content-id=amzn1.sym.1091e5b8-0ff4-492a-aa0b-7bc8b59253c6%3Aamzn1.sym.1091e5b8-0ff4-492a-aa0b-7bc8b59253c6&crid=2QQBCWZ7AM6BX&cv_ct_cx=phone%2Bbike%2Bmount%2Bflexible%2Biphone%2B16%2Bpro&keywords=phone%2Bbike%2Bmount%2Bflexible%2Biphone%2B16%2Bpro&pd_rd_i=B0BNBLCWL2&pd_rd_r=52d9dc15-f237-439c-8cf1-759198ae7b11&pd_rd_w=JvXLL&pd_rd_wg=bl2MK&pf_rd_p=1091e5b8-0ff4-492a-aa0b-7bc8b59253c6&pf_rd_r=FY1KRRHVJMNH1XM1FVGC&qid=1743731946&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=phone%2Bbike%2Bmount%2Bflexible%2Biphone%2B16%2Bpro%2Caps%2C97&sr=1-4-6024b2a3-78e4-4fed-8fed-e1613be3bcce-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&th=1) was selected and traced in Fusion 360. Once extruded, the component was scaled to fit an iPhone 16 Pro.<br><br>

When printing this component, an FFF printer was used. 90 TPU was selected as the filament rather than 95 TPU as it allows for increased flexibility, allowing the phone to be gripped more securely. 


### CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a499a8c2dbb0b748e5?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


## Assembly Instructions

{% include gallery id="gallery2" caption="1) Clamp Part; 2) Detent Gear; 3) TPU Part" %}

1.	Embed a heat set insert into the center (chamfered) hole of the Clamp Part.
2.	Place a 15 mm long, 5 mm diameter compression spring into the spring box in the Clamp Part. Balance a 7 mm ball bearing on top of this spring.
3.	Place the Detent Gear in the Clamp Part, slightly compressing the spring to allow the holes to align. Secure with a 12 mm M5 bolt, leaving some space for the Detent Gear to rotate freely.
4.	Stretch the center of the TPU part over the lip of the Detent Gear.
5.	Use a 16 mm M5 bolt and M5 nut to secure the clamp to the handlebars. 
6.	Stretch the corners of the TPU Part around a phone to secure it in the clamp.<br><br>
To rotate the phone, simply push down into the spring and spin the phone to the desired orientation.


## Final Model


{% include gallery id="gallery3" %}

{% include gallery id="gallery4" %}


### [Project Website](https://new.express.adobe.com/webpage/wja0IBzZU85i3)
