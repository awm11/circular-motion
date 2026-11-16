# Circular motion: coin on a turntable

An interactive three.js simulation for A Level Physics. Friction provides the centripetal force on a coin sitting on a rotating turntable.

**Live:** https://awm11.github.io/circular-motion/

## Features
- Rotatable 3D view, plus a flat bird's-eye view
- Sliders for angular velocity (rad/s or Hz), radius, mass, static friction (the surface changes from metal to wood, cork, rubber and sandpaper) and force arrow size
- Force arrows (friction, weight, normal reaction, force needed) and a velocity arrow
- Slipping model: static friction holds the coin until mω²r > μₛmg. After that, kinetic friction acts against the coin's motion relative to the surface, so the coin spirals outwards and flies off
- Trails in the ground frame and/or the turntable frame
- Live values, a gauge of force needed ÷ maximum friction, and worked equations

It's a single self-contained `index.html`. three.js loads from the jsDelivr CDN.
