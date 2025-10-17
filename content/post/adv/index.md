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

Since today's class was 75 minutes, we had a soldering party. (˵ •̀ ᴗ •́ ˵ ) ✧  Mr. Dubick went through a quick tutorial reviewing soldering basics, including using solder flux to improve solder joints. We first practiced soldering 3 through-hole resistors vertically on a protoboard.

<center>
<img src="practicesolder.jpeg" width=500>
</center>


Once our soldering got approved, we began working on a soldering kit, which had a mix of through-hole and surface mount components. I hadn't surface-mount soldered since this past summer, so I used a multimeter on the continuity setting to make sure I didn't create any solder bridges. Overall, this was pretty fun and an awesome opportunity to review soldering fundeamentals. I also challenged myself to finish the entire kit within the period!

![Front side of the owl PCB, containing the main electronics and the surface-mount components](frontowl.jpeg) ![Back side of the owl PCB, containing the LEDs](backowl.JPG)

The last step of the kit was to install the M3 screws and standoffs, allowing the PCB to sit upright. 

<center>
<img src="standoff.JPG" width=400>
</center>

Here is a video of the final kit working:

<center>
<video width="500" height="300" controls>
  <source src="pcbowl.mp4" type="video/mp4">

</video>
</center>

Fortunately, I didn't experience any setbacks during this process (though it was very tedious to solder all of the LEDs).


### 09/30/25-10/1/25

I discussed with Mr. Dubick, and he suggested some alternative temperature sensors, including digital sensors, thermocouple, and thin-film RTD (PT1000). These solutions offer higher-precision measurements but are typically more expensive and harder to integrate into wearable technology. I looked into PT resistance temperature detectors (RTD), which reliably correlate the resistance of platinum with measured temperature. I read [online](https://www.dwyeromega.com/en-us/resources/rtd-pt100-vs-pt1000) that the PT100 is better suited for 3-4 wire configurations, and unwanted resistance from lead wires and connectors will have a larger distorting effect on overall resistance measurements. On the other hand, PT1000 has a much greater resistance, meaning that it's less vulnerable to resistance distortion.

### 10/06/25-10/07/25

Today, I wrote up the [Bill of Materials](https://angelinayyang.github.io/p/nerve-conduction-study-temperature-monitoring-sleeve/#bill-of-materials-bom) for this project. Afterwards, I communicated with Mr. Dubick and purchased two preliminary PT1000 RTDS.



### 10/09/25

Today, I designed a basic schematic/conceptualization of my design, which includes 1 ADG1408 8-1 multiplexer, 1 ADS1261 Analog-to-Digital converter, and the main MCU. You can access the text version of the schematic [here](https://angelinayyang.github.io/p/nerve-conduction-study-temperature-monitoring-sleeve/#proof-of-concept). I intend on using the MUX to select each leg of each RTD in the array, before sending the signal through the ADC.

### 10/10/25

Today's class was a 75-minute block, and I'm waiting on the RTDs to arrive, so I went through the formal rubric and completed the design specification considerations. You can access them [here](dsc.pdf). I also designed a [gantt chart](https://docs.google.com/spreadsheets/d/1M1naMrrbnOMg5gQO8-gfPohlKmZIxycnOxSoGX8i0pI/edit?usp=sharing) to monitor the progression of this project. So far, I'm on track with my timeline, and I look forward to begin prototyping once all of my components are delivered! Since I plan on using the 1.8" TFT LCD, I decided to spend the remainder of claess exploring the ST7735 and the Adafruit_GFX library. I wrote up a sample code that initiates the TFT and displays a simple text.

```


#include <Adafruit_GFX.h>    // Core graphics library
#include <Adafruit_ST7735.h> // Hardware-specific library for ST7735
#include <Adafruit_ST7789.h> // Hardware-specific library for ST7789
#include <SPI.h>

// define the SPI pins for the Arduino Uno
#define TFT_CS 10
#define TFT_DC 9
#define TFT_RST 8


Adafruit_ST7735 tft = Adafruit_ST7735(TFT_CS, TFT_DC, TFT_RST);


void setup(void) {
  Serial.begin(9600);
  Serial.print(F("Hello! ST77xx TFT Test"));


  tft.initR(INITR_BLACKTAB);      // Init ST7735S chip, black tab
  tft.setRotation(1);
  Serial.println(F("Initialized"));


  tft.fillScreen(ST7735_BLACK);

  tft.setTextWrap(true);
  tft.setTextSize(2);
  tft.setTextColor(ST7735_WHITE);
  tft.setCursor(10, 10);
  tft.print("Hello World!");


}

void loop() {

}


```

### 10/14/25

Today, Mr. Dubick went over the process of using Github Pages to develop our digital portfolio sites. Since I already set up a site, and I'm waiting for the RTDs to arrive, I worked on side project during class. On Youtube, I've been watching a lot of videos from the [Nerd Musician](https://www.youtube.com/@NerdMusician), and I similarly wanted to design a MIDI player and record some music my STEM maker portfolio. I designed a basic schematic of the main board, which uses an Arduino Nano board as the microcontroller:

<center>
<img src="midischematic.png" width=500>
</center>

After assigning footprints, I arranged all of the components in the PCB layout editor. I then tried to route this board, but for some reason, Kicad kept crashing whenever I drew a trace. 

### 10/15/25

We had today off due to PSATs, so I continued working on MIDI PCB. I found that the KiCad crashing issue was related to an overloaded cache, so in terminal, I ran the following command:

```
rm -rf ~/Library/Caches/kicad

rm -rf ~/Library/Preferences/kicad

rm -rf ~/Library/Application Support/kicad
```

and this resolved the problem. In the PCB layout editor, I routed the MIDI PCB, using my standard constraints and .5mm width tracks. Some of the footprints, such as the [CherryMX key switch](https://github.com/sszczep/kicad-libraries), weren't previously available in KiCad, so I had to manually import them. Since all of the components are through-hole, I made use of both the front and back side.

<center>
<img src="midipcb.png" width=500>
</center>

Here's the projected BOM for this project:

| Part Name | Cost | Quantity | Source |
| :---------: | :---------: | :-----: |:--------:|
| PT120 Linear 10kΩ Potentiometer | $1.42  | 5 | [Digikey](https://www.digikey.com/en/products/detail/tt-electronics-bi/P120PK-Y25BR10K/5957454)|
| White Micro Potentiometer Knob - 4 pack | $2.95 | 2 | [Adafruit](https://www.adafruit.com/product/5538) |
| Slide Potentiometer with Plastic Knob - 45mm Long - 10KΩ | $1.95 | 1 | [Adafruit](https://www.adafruit.com/product/4272) |
| 1206 SMD LEDs | $0.36 | 6 | [Digikey](https://www.digikey.com/en/products/detail/liteon/LTW-C230DS/3198820) |
| 1206 SMD 330Ω | $0.21 | 6 | [Digikey](https://www.digikey.com/en/products/detail/rohm-semiconductor/KTR18EZPF3303/1983725) |
| Arduino Nano Every Development board | $12.90 | 1 | [Arduino Store](https://store-usa.arduino.cc/products/nano-every?srsltid=AfmBOor4duAdkQ7W_REHfcpkdtGwOyXQd2NoSeVBtsPD7mocRG2U5cxd) |