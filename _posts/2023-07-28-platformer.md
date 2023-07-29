---
layout: post
title:  "random game design thoughts"
dateInformal: "July 28, 2023"
author: "Pengalu, Co-developed by Hueblu"
category : "Untitled Cyberpunk Project"
---
# This project has no name.

It will not have one for the forseeable future. Naming projects is for people with rationality, which I don't have. I intended for this game to be my "main" summer project, but ended up getting too wrapped in with photography and gamejams to actually get shit done, except for one night at like 5 AM where Hueblu and I worked at it nonstop for no reason. Anyways, that's besides the point, let's get to the actual meat and potatoes of this project.

## The Concept

A movement shooter, but in 2D. A combination of typical action-roguelike bullethell elements, like dodging hailstorms of slow projectiles, large hordes of meaty enemies, etc. combined with elements from games like Ultrakill, Get To The Orange Door, and Titanfall (2). 

### Movement? How?

A "movement shooter" in 2D doesn't really sound like a very good concept in all honesty. Movement shooters are realistically only possible because of 3D. Verticality can't really be achieved from a top down perspective, and using an isometric perspective might as well just be a 3rd person perspective at that rate. However, with this project, I aim to condense my favorite part about movement shooters into the main mechanic of the game- one that doesn't require any verticality whatsoever, momentem. The game revloves less around actually building up speed than maintaining it. The character accelerates slowly, but can get a bit of a boost from their dash, however, once you get going in one direction, pivoting backwards or even to the sides can be difficult. The main use of the dash is not to build speed, but rather to quickly pivot directions. The dash redirects ALL momentum in the current direction towards the new direction being inputted. Dashes become a valuable tradeoff between getting up to speed and actually being able to keep it going. If you're bounding towards a wall and need to change course, you'll have to dash or risk losing all your momentum. But, of course, why would you opt to go fast in the first place? While games like DOOM make enemies less accurate the faster their target is moving, we've decided to opt for using your momentum as a tool that you can trade for damage avoidance through sliding.

### Sliding

While maintaining your momentum is the core movement challenge in this game, the actual reason you'd want to maintain speed is ultimately to slide. Your character decelerates extremely fast during slides, and is practically unable to turn, given very little sideways steering input, however, you are completely immune to all forms of damage during a slide. Bullets, explosions, flying sawblades? No problem. Just hit the ground and pass straight through 'em. Your dashes don't provide invulnerability like your slide does. The acceleration might help you dodge a couple projectiles, but sliding has no cooldown. As long as you have enough momentum, you can slide. You'll have to build up speed, preserve it using your dashes, and slide at the right moments to drop right under bullets and plow through enemies. Picking yourself up mid-slide just to go back into another one in seconds is expected. You can opt to use a long, extended slide until you're out of momentum in order to dodge large clumps of hazards or use carefully timed, short, repeated slides to pass through individual threats and maintain more of your momentum. 

## Combat

Now that we've gone over movement, it's probably worth mentioning combat. In all honesty, it's much less set in stone what we want to do with this, but we know we want some sort of ranged-melee hybrid like what's seen in Hyper Light Drifter. 

### Current Concept (Subject to Change)

Your right click is bound to a sword, which takes about 5 seconds to charge between uses. If it hits an enemy, they are stunned, knocked backwards, and you enter a Zelda BOTW esque barrage where time slows down and you can rapidly unload your gun into the unfortunate bad guy who happened to fight the wrong protagonist. It should be noted that for more swarm-like enemies who'd die to one or two bullets anyways, the sword might just kill them outright to prevent them from cluttering the game too hard. You can also use your gun- bound to left click- outside of the barrage, however, the gun is much more of a ranged pestering tool at that rate, since you don't have the bullet time to let you dish out high amounts of damage quickly. You can use it to interupt enemy attacks and pick off enemies from a range, but if you want to kill stuff faster, you'll have to get up close and personal, encouraging the use of movement so you aren't hit on your approach and as you retreat to let your sword recharge. Possible progression might allow for more actions during a barrage- follow up melee attacks, stunning other nearby enemies, allowing you to shoot them as well, etc. This simple gameplay loop incentivizes good movement skills, forcing you to make a path in and out of range in order to get a good amount of damage off. 

## Graphical Style

I forgot to add this anywhere so I'm just slapping it down here. The game technically runs in 3D. It rasterizes down to give the appearance of 2D pixel art. This is mostly so we can create clear and concise animations and create levels much quicker than hand pixeling it all. (and also to provide some cool neon light effects for the whole cyberpunk theme) Right now, it looks... okay? It's whatever, we'll sort it out later, but it does render down to something roughly like how we want it, maybe we'll need to tweak it but for now it's not really noticable.

## Final Notes

It's 1 AM and I'm tired and wanna stop writing. The game is currently EARLY into development, we have movement down and tuned, some extremely programmer art-esque animations and 3d assets, and some basic lighting that we wanted to play around with. I do have high hopes for this project, ever since we conceptualized it early this year, it's been on my mind non-stop. Now that I have time to work on it, I'm confident I'll get it done eventually. Preferably before college. Who the fuck knows, time is relative, and I don't really care as long as I have something to motivate me.

Signing off,
-Peng (hue wasn't here when I wrote this shit)