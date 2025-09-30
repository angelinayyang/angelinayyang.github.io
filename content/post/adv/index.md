---
title: Advanced Topics in Engineering Documentation 
description: Senior year engineering documentation and project development
image:
date: 2025-08-25

categories:
    
tags: 
    - daily journal
    
weight: 3      # You can add weight to some posts to override the default sorting (date descending)

---

Welcome to my daily journal! Here, you will find my day-to-day progress in advanced engineering! ヾ(・-・*)

## Semester 1

### 08/27/25

Today, I began the pen turning project. I selected four types of wood I wanted to incorporate into my wood pen, including cherry, purple, coffee, and light-beige colored wood. After marking off measurements on each piece according to the length of the brass tubes (2⅛”), I used the bandsaw to cut them. I applied glue between each piece and clamped them down, leaving them to dry for ~24 hours.




<center>
<img src="wood.png" width=400>
</center>

### 08/28/25

Seeing that the individual wood blocks were adhered together, I drilled a hole through both of my wood columns using the wood lathe with a drill bit extension. Then, I sanded the brass tubes using a low-grit sandpaper, applied super glue externally, and inserted them into the wood holes. To ensure that the tubes were flush with the wood, I tapped both columns on the table.



<center>
<img src="drilledwood.jpeg" width=400>
</center>

### 09/03/25

Today, I turned my two wood pieces that make up my pen on the lathe. I sanded down the corners of the two pieces beforehand, which would allow me to smoothly trim the wood's original square shape to its final cylindrical shape. Installing the two columns into the lathe, I started by using the rectangular tool, angling it downwards to take off more material. At first, the wood would stop whenever the tool made contact with it; however, this issue was resolved when I further tightened the lathe. Once I had trimmed off around 3/4 of the wood, I switched the circular tool to make precise changes, such as shaping the ends of the wood. Then, I began polishing the wood, using rough sandpaper (~120), before slowly moving up to ~320, ~600, ~1000, and eventually ~2000. 

![Wood columns installed on the turning lathe](woodonlathe.jpeg) ![Wood columns shaped into cylinders via the rectangular tool](roundedwoodonlathe.jpeg) ![Final wood columns refined via the circular tool](shapedwoodonlathe.jpeg)


I used a paper towel and applied wood finisher to both of the components. After taking off both pieces off of the lathe, I noticed that one of the brass tubes was a bit longer than the wood, but this ended up not being a big issue during the assembly process.



<center>
<img src="sanded.png" width=400>
</center>

### 09/04/25

Today, I assembled my pen with the push press. This was a rather quick process, as I simply needed to organize the individual pieces into the correct order and manually press them together. Once all parts were assembled, the pen could easily open with a twist!

<center>
<img src="pushpress.jpeg" width=400>
</center>

Here is the final pen assembled and ready to use:

<center>
<img src="finalpen.jpeg" width=400>
</center>

For the remainder of class, I drafted an updated email to Rhythmlink asking about this year's assignment. Additionally, I began tinkering in Adobe Illustrator, learning how to adjust document dimensions, draw vector shapes, and add text. I laser cut 6"x4" rectangle with a cut-out circle and my name engraved in the center. I thought Adobe Illustrator was pretty intuitive to use, but I definitely need to practice more!


### 09/05/25-09/09/25

During these classes, I brainstormed potential final project ideas, in the case that Rhythmlink didn't have an assignment for me. I looked into using an array of gas sensors to detect the presence of volatile organic compounds in exhaled breath, as a way to diagnose early-stage lung cancer.

### 09/10/25-09/19/25

Rhythmlink responded with a new assignment for me! („• ᴗ •„)

 On September 10, we began our introduction to Github, learning about version control, pushes/pulls, and different use cases. We watched a video tutorial, before creating our own repositories through Github desktop and making changes via Visual Studio Code. At this point, I had already created my main documentation repository, so I created a new repository for Rhythmlink. I also wrote up a short README.md with the action items for this year's assignment, as well as a high-level plan with a proof-of-concept. I shared both of these repositories with Mr. Dubick as a collaborator. I also began sketching out some designs for Rhythmlink. Since this year's project meshes functionality with wearability (i.e. how comfortable the product is), I mainly explored two elements of the project: a] sleeve material, and b] the type of temperature sensor. During this time, I stumbled upon this [Adafruit tutorial](https://learn.adafruit.com/wearable-temperature-monitor/overview), which embedded an MCP9808 high-precision temperature sensor into wearable arm band. I thought this was a neat starting point; however, I soon realized that because the sensor itself was so small in size, the readings would be inconsistent if the user wore the sleeve differently between each use. Another option I found was Adafruit's [ultra-thin thermistor](https://www.adafruit.com/product/4890?srsltid=AfmBOorrWaWLpQRxIvUpXYDWa7W9t47vGihrr80alzbG9IhYHmo-TxhxpeA), which detects changes in resistance and correlates that to temperature shifts. As of now, I'm not sure which option will be better. In terms of sleeve material, I took inspiration from [blood pressure cuffs](https://www.amazon.com/Pressure-Compatible-8-7-12-6-Replacement-Connectors/dp/B0D1QGNG6Q?th=1), which consisted of an inner-layer of softer material (e.g. modal) and an outer-layer of durable nylon. I think it'd be really interesting to integrate kapton flex PCBs (containing the temperature sensor) into the fabric!


 ### 09/24/25

 Today, we learned about pull requests, which is an effective mechanism for merging branches (i.e. copies of a repository) when collaborating with others. Mr. Dubick introduced the basic workflow for pull requests, and we had the opportunity to test it out afterwards with a partner. I found this really helpful, since I didn't have a lot of experience with pull requests/branches in the past. In the remaining class time, I continued exploring options for the temperature sensor. After looking through some past research papers, I learned that [flexible temperature sensors](https://www.mdpi.com/1424-8220/18/5/1400) have been engineered in the past using biomaterial like reduced graphene-oxide. This option seems to operate in a similar fashion as a thermistor, but it also seems to produce more accurate results. Since this would be difficult to reproduce within the Fab Lab, I'm wondering if I can reach out to a local lab (e.g. UNCC) to make it.

 ### 09/25/25

Since today's class was 75 minutes, we had a soldering party. (˵ •̀ ᴗ •́ ˵ ) ✧  Mr. Dubick went through a quick tutorial reviewing soldering basics, and we first practiced soldering 3 through-hole resistors vertically on a protoboard. Once our soldering got approved, we began working on a soldering kit, which had a mix of through-hole and surface mount components. I hadn't surface-mount soldered since last year, so I used a multimeter on the continuity setting to make sure I didn't create any solder bridges. Overall, this was pretty fun, and I challenged myself to finish the entire kit within the period!

![Front side of the owl PCB, containing the main electronics and the surface-mount components](frontowl.jpeg) ![Back side of the owl PCB, containing the LEDs](backowl.JPG)

The last step of the kit was to install the M3 screws and standoffs, allowing the PCB to sit upright. 

<center>
<img src="standoff.JPG" width=400>
</center>

INSERT VIDEO OF KIT WORKING






