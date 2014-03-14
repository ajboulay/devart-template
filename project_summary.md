# Project Title
Multiverse

## Author
- AJ Boulay, https://github.com/ajboulay


## Description
A Universal Design accessible to everybody, Multiverse is a chance to interact with thousands of parallel universes in 3D Virtual Holograms. Holographic Quantum Neural Networks control this misted 3D environment, and learn with the visitor as they interact and build the many parallel universes. The misted interfaces create an interactive hologram in 3D. Multiverse pushes the boundaries of code and technology by exploring how human brains, Artificial Neural Networks and new interactive 3D VR come together with real people who may discover the secret of how our Minds are interconnected with the Universe. The building of Multiverse is done by its visitors, but the answers it communicates may belong to the Universe, and this is the greatest motivation: Here code may reveal the magic of reality, and programming makes magic turn into real things.  

## Link to Cover Image
NOTE: If your project lives online you can add one or more links here. Make sure you have a stable version of your project running before linking it.

[Image Link](http://computationalsciences.wordpress.com/208/)

## Example Code - Configuration File for one of the Neural Networks 

NODES:
nodes = 16
inputs = 8
outputs = 8
output nodes are 1-8
CONNECTIONS:
groups = 0
1-8 from i1-i8 = 1. & 1. fixed one-to-one
9-16 from 1-8 = 1. & 1. fixed one-to-one
1 from 10-16
2 from 9, 11-16
3 from 9, 10, 12-16
4 from 9-11, 13-16
5 from 9-13, 15, 16
6 from 9-14, 16
8 from 9-15 
SPECIAL:
linear = 9-16
bipolar = 1-8
selected = 1-8
weight_limit = 0

```
## Links to External Libraries
 NOTE: You can also use this space to link to external libraries or Github repositories you used on your project.

[Example Link](http://www.google.com "Example Link")

## Images & Videos
NOTE: For additional images you can either use a relative link to an image on this repo or an absolute link to an externally hosted image.

![Example Image](project_images/cover.jpg?raw=true "Example Image")

https://www.youtube.com/watch?v=30yGOxJJ2PQ
