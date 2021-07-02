# lichie.lorenzattractor
Standalone Chaotic Lorenz Attractor built in gen~ and MaxMSP 

![image](https://user-images.githubusercontent.com/77128423/124221437-b269fd80-daf7-11eb-9866-a40718998b69.png)

A chaotic modulation source for synthesizers
standalone version of the attractor found in my granular synth patch.

Based on three linear equations: 

dx = a * (y - x) * dt

dy = (x * (b - z)) - y * dt

dz = (x * y) - (z * c) * dt

There is control over variables a, b and c and the speed of the attractor. Small changes to these values produces vastly different results. 

The patch only displays the dx and dy on the [scope~] object however, all three outputs are available as modulation sources. 

