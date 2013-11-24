---
layout: post
title: "Rower: a rowing simulator"
date: 2013-11-24 01:34:54 +0100
comments: true
categories:
 - recreation
 - DiY
 
---

Having small kids and *cranky wife* (sory Mojca :-)), my physical activity was reduced to minimum in the last year. When my brother bought a rowing simulator [Water rower](http://www.waterrower.com/) I instantly wanted to have my own. These machines come at a price however. So I decided to build one of my own. Its mostly wood, so how hard can it be.

The idea
--------

So, the design of the Water rower is really simple:
 
 * two planks serve as a rails for the troley
 * the troley is a simple wooden box
 * the paddle handle is fixed by a 2cm belt
 * the belt winds from a reel, which rotates a paddle inside a bucket of water
 * at the bottom, there is an bungee elastic, which rolls back the belt at the end of the stoke
   
The clever part of this design is the *paddle rotating in water*, which creates a resistance close to that on the real rowboat. This part of the design is also a major obtacle for DIY design. To create watertight container with rotating paddles inside would be too much for my level of skills.

The nature of the Force
-----------------------

After finally discarding the idea of building the water container, I started to think with what I can replace it. People made similar devices with bungee elastics. But the elastic produce the force proportional to the change of its length. So at the end of the stroke, the force would be the biggest. The force I would be pulling would be 
 $$F_e=k\cdot x$$
where x is the length I would extent the elastic when I would pull the handle.
 
Appart from that, the elastic save most of the energy needed for the extension and that energy is returned at the second part of the stroke. When rowing however, no energy is returned to the rower. All the enery gets dissipated by the resistance of the water. 

Resistance is quite a different kind of a force. It is proportional to the velocity:
  $$F_r = -\kappa \cdot \dot{x}.$$
Ok, if you row very fast, the quadratic law of resistance would apply. Water rower solved this with a brilliant idea to use water for the resistence, while other manufactors use fans, which move air through smal holes, to create similar kind of force.
 

Finding the Force
-----------------

So I start walking like professor Baltazar in the cartoon, to figure out what could be used to produce the kind of resistence I needed. And then as in the cartoon it came into my mind, that bycicle trainers offer the same kind of resistence. I have one at home, that uses oil chamber to use viscous force of oil, to create resistance. Sounds familiar to paddles in a woter tank :-) The trainer is [Elite Super Crono](http://www.elite-it.com/products/). Even if you buy a new one, it would cost around 250€, so there is quite a margin to the original [Water rower](http://www.waterrower.com). This is the first sketch 

{% img images/wr-sketch.png %} 
