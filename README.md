### Simple Physics Engine in Javascript

#### Features:

- Standalone, requires no external libraries or plugins
- Easy grouping of objects and collision policies
- Can use canvas; SVG, WebGL, or even DHTML should be doable


#### Overview:
  
The Physics Engine is made up of a World, which contains Groups and Particles.

The World can set global attributes such as gravity and forces.

A Particle is the most basic form of object in the world.

Circle and Rectangle are Particle subclasses.

Group groups particles with similar attributes (what's collidable with what).
  Thus, groups are more like tags, not folders.

See each file's documentation for more info.

To generate new single file source spe.js after modifications, install python and run:
python generate_spe.py


#### Demos:

using canvas as renderer - <a href="http://johnleung.com/project/simple-physics-engine/">live demo</a>.
