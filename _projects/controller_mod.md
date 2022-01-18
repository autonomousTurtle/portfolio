---
title: 'Nunchuck'
subtitle: 'RC Truck Modification to use Wii Nunchuck'
date: 2018-06-30 00:00:00
description: A project for May We help and Joe Nuxall Miracle League, this putter is fully remote controlled. Using a unique control from Microsoft, the robot can easily be moved around and putt the ball! 
featured_image: '/images/controller_mod/controller_mod_featured.png'
---

![](/images/controller_mod/controller_mod_featured.png)

## RC Controller Adaptation

This project was for May We Help. The objective was to take an existing RC car controller for a toy dump truck and modify it so that it could be used with just one hand by adding a Wii Nunchuck. 


### Initial Controller (Before Modifications)

<img src="/images/controller_mod/initial_controller.jpg">

The initial controller design was fairly simple, all of the joysticks and buttons on the surface just pressed digital buttons on the controller PCB. 

### Modifications

To make the nunckuck work, an arduino teensy was used to interpret the nunchuck button inputs over I2C. It then sent digital outputs to MOSTFETS whose outputs interrupted the push button signal on the controller PCB, tricking the controller into thinking a button was actually pushed. This was then communicated to the RC car without ever modifying the car or RF components in any way. 

<img src="/images/controller_mod/Artboard_nun.png">


#### Components

* Teensy 2.0
* Wii Nunchuck 
* Wii Nunchuck Adapter
* MOSFETS
* 3D Printed Controller Interface

---

### Image galleries

Here's a really neat custom feature we added – galleries:

<div class="gallery" data-columns="2">
	<img src="/images/controller_mod/controller_top_view.jpg">
	<img src="/images/controller_mod/micro_controller.jpg">
	<img src="/images/controller_mod/nunchuck_insert.jpg">
	<img src="/images/controller_mod/prototype1.jpg">
</div>

## Pretty cool, huh?

We've packed this theme with powerful features to show off your work.

Why not put them to use on your new portfolio?

<a href="https://jekyllthemes.io/theme/board-portfolio-jekyll-theme" class="button button--large">Get This Theme</a>
