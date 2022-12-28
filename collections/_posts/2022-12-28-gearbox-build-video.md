---
layout: post
title: "Version 1 Drive Unit — Design + Build Video"
date: 2022-12-28T11:11:11Z
authors: ["Adi Mehrotra"]
categories: ["Engineering"]
description: Motors, belt drives, and white-lithium grease. 
thumbnail: "/assets/images/gen/blog/gb-1.png"
image: "/assets/images/gen/blog/gb-2.png"
comments: false
subscribe: true
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/94Xf_wgISU4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Our goal for the next few months is to develop a version 1 prototype of a hydrogen powered motorcycle so we can begin to characterize such a system and verify our design methodology. Over the past six months we've been working on the first iteration of the main drive unit.

# Drive Unit Version 1

The drive unit is a modified gearbox from a Ducati 900SS chosen because the gearbox of the bike is structural (as in the rear swing-arm mounts to the gearbox). Designing and manufacturing a new gearbox with swing-arm mount capabilities was too much of an investement for a first prototype so we designed around the existing casing. 

![Gearbox belt system from the above video](/assets/images/gen/blog/gb-3.png)

The drive unit contains two T-Motor U15s putting out a maximum of around 7kW each. The motors are belted together through a 1:1 drive reduction, and then the shaft driven by both motors is belted to an output shaft that drives the main chain through a 1.4:1 belt reduction geared for torque. Each motor is controlled by its own, off the shelf, 200A-VESC motor controller. The off-the-shelf motor controllers will be used in version 1, and we will switch to a custom inverter in the future. 

![T-motor with dowel pins being glued](/assets/images/gen/blog/gb-4.png)

Torque transfer was done with either dowel pins from motors to hubs, and hubs to pullies, or directly through the 1/2" Aluminum Hex-Shaft construction of the gearbox. In the future we will be adding a "hat" for the gearbox that contains both motor controllers, all the wires, as well as the battery management system and any power converters needed for the rest of the bike. Note that more details on the design will be presented on the documentation pages for the Power Unit when they are released, we just need some time to verify the system and test it on real hardware before compiling the documentation. 

