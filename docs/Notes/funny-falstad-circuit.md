I was playing around with the falstad circuit simulation aimlessly, and had made a simple saw oscillator circuit, but then I decided to add a 100k resistor between the capacitor and ground. I have no idea what it will do in real life, but in the simulation it managed to bend time. 

Note that in the scope, the speed that time passes will change

```
$ 1 0.000005 75.37042125545614 50 5 43 5e-11
183 240 288 320 288 0 0.5 1.67 3.33 5 0
c 240 288 240 336 4 2.2000000000000003e-9 2.818264536718179 0.001 0.1
g 304 336 304 352 0 0
d 320 256 240 256 2 default
w 240 256 240 288 0
w 320 256 320 288 0
w 240 256 240 224 0
a 240 208 336 208 8 12 -12 1000000 2.8010930472453035 2.8011210581757755 100000
w 240 192 240 160 0
w 240 160 336 160 0
w 336 160 336 208 0
c 336 208 400 208 4 0.000001 3.276084557944754 0.001 0
r 400 208 400 272 0 100000
g 400 272 400 288 0 0
O 512 208 560 208 0 0
w 400 208 512 208 0
r 240 336 304 336 0 100000
o 14 32 0 4098 2.5 0.1 0 1

```