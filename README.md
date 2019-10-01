# Final Project PGS 🐑

I focused on the lecture 01_intro/Houdini. During the project development process I dealed with the topics of **modelling** and **rigging** in Houdini to create a basic digital asset. The result could build a base for animators to animate a scene with the modeled object. To deliver the animation department a polished result the used subnetwork includes a parameter list with the controls that are allowed to use. All others are locked. 

Please find the parameter list like this:

right click on the subnetwork > Parameters and Channels > Parameters...

![pf_smaller](https://user-images.githubusercontent.com/22836416/65829084-c7ba5400-e2a1-11e9-8a73-b09e7278e41f.gif)

To model the sheep I drew small sketches, followed by mostly try and error modelling in Houdini. To rig the model I mainly used the [SideFX human rigging series](https://www.sidefx.com/learn/collections/rigging-series/) and updated it later based on some parts of the [SideFX cat rigging series](https://www.sidefx.com/tutorials/author/Bj%C3%B8rn%20Blaabjerg%20S%C3%B8rensen/).

If you are interested to see the project progress, you can find it in the [blog.md](./blog.md). For following future development check [this repo](https://github.com/Franziska-Paetzold/Houdini/).


## Discussion

During modelling the different body part I became more confident because I experienced the use of different tools. I understood Houdinis structure better and with the time I knew where to search for the tools I was looking for. Looking back, modelling with basic knowleadge of rigging would happen a little bit different, because I now know that I need some more seperated primitives here or there. 
All in all I learned a lot about  parameters in Houdini and feel more confident to use expressions in parameter fields. Also, I learned how o use own shelfs and to extend them.

Capturing the the geometry would have given the model a smoother look after translating a rig, but unfortunately it doesn't work with my model for now. This is why I stay with the option of different groups of the model connect to the bones, which gives the model a nice old fashined look after it is transformed:

I took focus on refactoring the spine-model connection, the leg rigs etc then ...

Sheep nect level

I did a lot of steps again and again and again, alone the legs (times four) were rigged for minimum seven times.

The projects result could be improved by some more tests of the rig functionality and some fixes are needed, for instance the master rotation. Also some more controls could be added and a rig for the tail, the ears, eyes and jaw or twists for the leg IKs.

Much fun with the sheep asset. 