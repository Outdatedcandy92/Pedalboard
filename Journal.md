# DIY Pedalboard

## What am I making?
I'm making a fully DIY guitar pedal board. My plan is to design a set of pedals and then also design a board for it (pedal-board!).
The current plan is to have about 6 effects in total, a dedicated DC power supply for them, a custom designed board made using aluminium extrusions to house the pedals and and everything.


Tuner->Distortion->Fuzz->Chorus->Loop->EQ->Noise Gate

## Time Spent:

### Goals for this project
- [ ] Off the shelf and THT components for most pedals
- [ ] Dedicated power supply for the pedals




# Day 1 (17th May)

Since I already made a DS-1 pedal before I had experience with designing pedals and I also knew about stuff I should avoid adding in my design.
Some of those problems were -
- Having thin holes for the potentiometers
- Placing the potentiometer holes in the middle instead of at the edges
- Using holes to solder wire instead of having screw in terminals

To start with the project I made the DS-1 v2 schematics in kicad, the schematics for version 2 were similar to version one because the schematics just work!

I started out with PCB layout after finishing It. I always like to first start of with a rough layout to see how I can arrange my components and look at how I can improve from their and then restart the PCB layout again. 
This is exactly what I did for this design and by the end of the day I ended up with a layout that I liked.

The next step was routing everything together. Because I already made something like this I had experience and knew what to avoid while tracing. 
I carefully routed all the audio signals first, keeping the traces short and smooth. After that I routed my power traces, this time I made sure that the power traces were far away from the audio signal and that they also cross the audio traces are a 90 degree angle to reduce EMI and noise from the power trace radiating into the audio traces. This was a lesson I learned from making version 1, my power traces were routed improperly which introduced a 60hz hum from the cheap power supply into the audio signal, It worked fine but there was just a buzz which was a bit annoying.

This was the final result PCB design:
![image]

## Time Spent: 5 Hours

I was pretty locked in today!

# Day 2 (19th May)

I started working on designing the big muff pi schematic today. 

The big muff pi is pretty easy to make compared to a DS-1, and I finished making its schematics in like 30 mins.

After that I started working on the PCB for it. I again followed the same method I listed above of creating a rough layout then going to a finalized one. And this was the end result of the PCB.

![Image]

## Time Spent: 3 Hours




