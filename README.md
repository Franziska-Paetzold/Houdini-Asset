# Final Project PGS 🐑

_Sheep next level_

I focused on the lecture 01_intro/Houdini. During the project development process, I dealt with the topics of **modeling** and **rigging** in Houdini to create a basic digital asset. The result could build a base for animators to animate a scene with the modeled object. To deliver the animation department a polished result the used subnetwork includes a parameter list with the controls that are allowed to use. All others are locked. 

Please find the parameter list like this:

right-click on the subnetwork > Parameters and Channels > Parameters...

![pf_smaller](https://user-images.githubusercontent.com/22836416/65829084-c7ba5400-e2a1-11e9-8a73-b09e7278e41f.gif)

To model the sheep I drew small sketches, followed by mostly try and error modeling in Houdini. To rig the model I mainly used the [SideFX human rigging series](https://www.sidefx.com/learn/collections/rigging-series/) and updated it later based on some parts of the [SideFX cat rigging series](https://www.sidefx.com/tutorials/author/Bj%C3%B8rn%20Blaabjerg%20S%C3%B8rensen/).

If you are interested to see the project progress, you can find it in the [blog.md](./blog.md). For following future development check [this repo](https://github.com/Franziska-Paetzold/Houdini/).


## Discussion

During modeling the different body part I became more confident because I experienced the use of different tools. I understood Houdini's structure better and with the time I knew where to search for the tools I was looking for. Looking back, modeling with basic knowledge of rigging would happen a little bit different, because I now know that I need some more separated primitives here or there. 
All in all, I learned a lot about parameters in Houdini and feel more confident to use expressions in parameter fields. Also, I learned how o use own shelves and to extend them.

The projects result could be improved by adding controls and a rig for the tail, the ears, eyes and jaw or twists for the leg IKs. Capturing the geometry would have given the model a smoother look after translating a rig, but unfortunately, it doesn't work with my model for now. This is why I stay with the option of different groups of the model connect to the bones, which gives the model a nice old fashioned look after it is transformed:

![sheep1](https://user-images.githubusercontent.com/22836416/65989027-360d3b00-e489-11e9-9796-aae959943c2f.png)
![sheep2](https://user-images.githubusercontent.com/22836416/65989036-39082b80-e489-11e9-9a22-e60428a56f1d.jpeg)

Unfortunately, the eye-white is not cositent and will always berendered a  little bit different:

![sheep3](https://user-images.githubusercontent.com/22836416/65989039-3a395880-e489-11e9-9618-510ca2701c07.png)
![sheep4](https://user-images.githubusercontent.com/22836416/65989040-3ad1ef00-e489-11e9-9d09-5083907f26b1.png)


I did a lot of steps again and again and again, alone the legs (times four) were rigged for a minimum seven times. This was pretty time-consuming. But during the project development, I build a valid modeling and rigging base for the next project. 

Much fun with the sheep asset. 
