gradient.lua
=============

A quick library for adding basic gradients to Love2D. Just call require at love.load and you're done!

love.gradient.draw(function, mode, centerX, centerY, width, height, color1, color2[, angle, scaleX, scaleY])
============================================================================================================

**Function:**
A drawing function (like with love stencils).

**Mode:**
A gradient mode (linear, radial, angle, rhombus or square).

**Center X:**
The X center of your shape.

**Center Y:**
The Y center of your shape.

**Width:**
The width of your shape (regardless of rotation).

**Height:**
The height of your shape (regardless of rotation).

**Color 1:**
The back color of your gradient.

**Color 2:**
The front color of your gradient.

**Angle:**
The rotation of your gradient image (default: 0).

**Scale X:**
The scale factor for your gradient's width (default: 1, flip horizontally: -1).

**Scale Y:**
The scale factor for your gradient's height (default: 1, flip vertically: -1).

gradients.zip
=============

Contains the default gradient images. Unzip it in the same level as main.lua.
