---
title: "Formula Student Suspension"
excerpt: "The front suspension was designed and created to support premaunfactured wheel hubs, brake calipers, and steering knuckles."

header:
  image: assets/img/Suspension CAD Complete.jpg
  teaser: assets/img/Suspension CAD Complete.jpg
gallery1:
  - image_path: assets/img/Suspension CAD Iter 1.jpg
  - image_path: assets/img/Suspension CAD Iter 2.jpg
gallery2:
  - image_path: assets/img/Suspension CAD Iter 3.jpg
  - image_path: assets/img/Suspension CAD Arm Complete.jpg
gallery3:
  - image_path: assets/img/Suspension CAD Complete.jpg
gallery4: 
  - image_path: assets/img/Suspension Arm Outline.jpg
gallery5: 
  - image_path: assets/img/Suspension Completed.jpg

   
---
<br>
## Introduction

The goal of this project was to design and assemble the front suspension for a high school Formula Student car. Multiple iterations were needed in order to ensure that the design for the front suspension fit the purchased wheel hubs, brake calipers, and steering knuckles. <br><br>

The suspension was first designed using Autodesk Fusion's CAD modeling software. Then, the suspension was assembled using multiple different manufacturing processes. Finally, the purchased components were bolted to the suspension, and the suspension was bolted to the chasis of the car.


## Design

The front suspension went through 4 iterations. The first two iterations did not give enough room for the brake calipers and wheel hubs to have their full range of motion. These problems were resolved in the third iteration, but the shocks and steering knuckles still were unable to fit. In the fourth and final iteration, the clearances were adjusted to allow for the shocks and steering knuckles to fit while still fitting the rest of the parts. However, due to simulations, it was determined that the design would exert too severe of forces, so the frame that supported the suspension had to be modified to better handle the forces. <br><br>

{% include gallery id="gallery1" caption="Iterations 1 and 2"%}
{% include gallery id="gallery2" caption="Iterations 3 and 4"%}

To create the suspension, there is a top arm and a bottom arm. Both are connected with bolts to the frame such that they are able to move up and down. Each wheel has its own suspension so that each wheel is able to dynamically respond to the terrain. In between the two arms is the wheel hub. The wheel hub is enclosed in a machined box to allow for bolts to connect the pieces better. Each connection between the wheel hub box and arm uses a ball-and-socket joint, with one side of the joint attached to the top of the box and the other side attached to a plate that is welded to the arm. This allows the wheels to turn left and right while the suspension is able to move vertically. The wheel hub box also contains a small arm to which the steering column will be attched. Finally, the bottom arm has an additional cross-sectional piece to hold the shock. The other end of the shock is connected to the frame in between the two upper arm connections.

{% include gallery id="gallery3" %}


## Assembly

To assemble the arms, straight 1 inch circular tubing was used. On a sheet of paper, the shape of the arms was traced in accordance to the CAD design. Then, using those parameters, the tube was cut using a chop saw. Then, the midpoint of the piece was marked. This was used when the tube was bent to match the CAD design. Finally, the tubing was cut to match the angle of the paper such that the tube was perpendicular to the frame at the point of connection. To ensure those bends stayed, they were MIG welded. The connection point between the frame and the arms was purchased, and the component was welded to the arm as well. <br><br>

{% include gallery id="gallery4" %}

The rest of the suspension was fabricated using a plasma CNC machine. Using the files created on Fusion, the plasma CNC machine was able to cut the flat pieces of steel. For the frame, the base, four long tabs to connect the arms to the base, and two small tabs to allow the shock to be bolted to the base were cut on the CNC machine. The base included small holes to allow the tabs to fit properly and to allow for more structural welds. Additionally, the plasma CNC machine cut the two plates that were welded to the end of both the top and bottom arms, the plate that connected the shock to the bottom arm, and the wheel hub box. Finally, all of these components were MIG welded. Once all of the machined parts were assembled, the purchased parts were attached.


## Final Model

{% include gallery id="gallery5" %}


### [Project Website](https://new.express.adobe.com/webpage/wja0IBzZU85i3)
