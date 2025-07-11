Diversion MK_I (ALPHA State)
================
![Home](PIX/render_logo_1.png)
$\color{Red}{\textbf{My Disclaimer:}}$
--------------------------------
Diversion [dəˈvərZHən] is a [Switchwire](https://github.com/VoronDesign/Voron-Switchwire) <ins>mod</ins>. It is <ins>not</ins> an official Voron release, nor is it a scratch-built printer (it is based on the original Switchwire’s kinematics and construction). However, it is a project created with dedication and deep respect for the efforts of the entire community.

The Printer:
--------------
![Home](PIX/diversion_render_1.png)
The idea behind this project was to build a solid base using parts that are either easily accessible on the market or recycled from old printers that were lying around. I’ve always admired the subtle way the Voron Team designed their parts, but I wanted to exaggerate a bit while making a machine for my personal use.

The design is heavily influenced by improvements and modifications suggested by the community (credits for which can be found at the end of the page).

The basic hardware required for this build is similar to that of a typical Voron build. You will notice an excessive number of 6x3mm magnets (compared to a typical printer), which was necessary to achieve a clean and modular enclosure.

The Build:
--------------
The frame is similar to the Ender-to-SW conversion in the X and Z axes; however, the frame joints are blind joints this time. This helps with squaring (as long as the extrusion profiles have straight, unbotched ends) and improves rigidity.

Another distinctive feature is the use of 4080 C-beams for the lower part of the printer. Beyond structural integrity, they offer practical benefits such as deep channels for cable management on each side of the electronics bay and more mounting points for the XZ motor mounts.

The filter in this printer is a hybrid of nateb16’s [The Filter](https://github.com/nateb16/VoronUsers/tree/master/printer_mods/nateb16/THE_FILTER) and Nevermore's [Nevermore Micro V6](https://github.com/nevermore3d/Nevermore_Micro/tree/master/V6). The result is a compact component using an intact 5015 blower fan with a carbon cartridge that attaches to the plenum via magnets. The plenum neatly houses a female JST connector.

The enclosure is an attempt to improve on the original SW enclosure in the area that, in my opinion, had the greatest drawback: modularity. In Diversion’s enclosure, VHB tape is still used—but only to attach the magnetic brackets that hold it together. A large number of 6x3mm magnets were necessary to accomplish this, but now about 70% of the enclosure can be removed in under 30 seconds. The door hinges are 270°, easily detachable, and require no extra hardware—you just print them and assemble!

On the Y-axis, two parallel linear rails are used. They improve rigidity but require careful alignment (using the included brackets) to prevent binding during movement. An Ender 3 carriage drill jig is included, but the ideal option is to CNC the included Snowflake Y-carriage .step file.


BOM:
--------------
[Link](./docs/BoM.md)

Special Thanks to:
--------------------
+ Voron Team for providing a solid base to start from (The Original SW).
+ [Sooeeren](https://github.com/Sooeeren) for his valuable contribution with the BOM.
+ All of this loving 3D printing community on the Voron Discord servers.
+ Yenda and Strayr for the idea of the more robust x/z motors.
+ richardjm for his snap-latch-2020 mod, which is used with tiny modifications.
