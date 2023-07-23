---
layout: post
title: "Version 1 Battery Documentation Released"
date: 2023-7-23T9:00:00Z
authors: ["Adi Mehrotra"]
categories: ["Announcements", "Engineering"]
description: MIT EVT releases design details on Version 1 Energy Storage System (ESS) as well as additional tools for battery design.
thumbnail: "/assets/images/gen/blog/battery.png"
image: "/assets/images/gen/blog/battery2.png"
comments: false
subscribe: true
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/hdNO4Q_LAoQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

After a few months of work we're really excited to announce our version 1 battery system and its associated documentation! It's worth noting that this first version battery system is a *prototype system* that's mainly intended for us to collect data during the initial stages of research. It will be followed by a more complete, optimized, and detailed battery design within the next 6 months that's based on data collected from version 1, performance requirements of the vehicle, as well as simulation. 

### Version 1 ESS/Battery Specifications
- System Voltage: 50V (12s)
- System Capacity: 32Ah
- Cells: SPIM08HP (16Ah)
- Configuration: 12s2p

The associated documentation is split into two main components, detailed information on specifically the version 1 battery system itself, and tools developed for general battery systems development. Documentation specific to the version 1 ESS includes documentation on cell choices, mechanical design and structure, BMS system setup, and Mechanical CAD of the battery. This documentation is intended for *hobbyists to replicate this battery for use in light-duty electric vehicle systems.* 

Tools developed for general battery systems development include a document outlining cell internal resistance measurement, and methods for pack and module-level resistance matching to optimize battery performance. We have also released a **Python script that can take cell resistance data as an input, and output a resistance-matched pack configuration.** The output is not optimal, but we will develop the tool further for release in the next version. It is likely good enough for most applications on **Solar Car and FSAE teams, or hobby-grade vehicles.** But, it should likely not be used for commercial application at the moment.

**Please note that contributions to our documentation, and suggested edits for clarity or function are always welcome.**

## Documentation Links

[Version 1 Energy Management System Design + Docs](https://github.com/Licence-to-Fab/battery-design/blob/main/Documentation/Version%201%20ESS%20Docs.pdf)<i class="fa-brands fa-creative-commons"></i>

[Mechanical CAD for Version 1 ESS (STEP)](https://github.com/Licence-to-Fab/battery-design/tree/main/Mechanical-CAD/V1)<i class="fa-brands fa-creative-commons"></i>

[Individual Cell Resistance Data + Impedance Matching Script](https://github.com/Licence-to-Fab/battery-design/tree/main/Tools)<i class="fa-brands fa-creative-commons"></i>

[Procedures for Battery Internal Resistance Measurement + Matching](https://github.com/Licence-to-Fab/battery-design/blob/main/Documentation/Battery_Modeling___Internal_Resistance_Matching.pdf)<i class="fa-brands fa-creative-commons"></i>

[MIT EVT Battery Design Github Repository](https://github.com/Licence-to-Fab/battery-design/tree/main)<i class="fa-brands fa-creative-commons"></i>

