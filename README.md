# 8 Bit Filter
An implementation of one of the Spore effects described in GPU Pro #1. Hard one, yuck.

# Algorithm

It rounds up the color of each pixel based on the following formula:

color = round(screen.rgb * Bitlevel) / Bitlevel;

where Bit is a float. It works best if it's between 5-20.

I did something similar for vertex shaders in my Voxelizer repository.

# Example

![Animated Julia](Renders/Before.PNG "Before")

![Animated Julia](Renders/After.PNG "After")

# Consider buying me a coffee if you like my work (click the image)
[![Foo](coffee.png)](https://www.buymeacoffee.com/ZcRuWpUBf)



