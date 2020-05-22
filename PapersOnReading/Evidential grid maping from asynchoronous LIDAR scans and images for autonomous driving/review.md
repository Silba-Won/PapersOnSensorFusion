[toc]

## Title : Evidential grid mapping from asynchronous LIDAR scans and images for autonomous driving

### Related Work

1. Semantic segmentation via convolutional neural networks
2. Evidential occupancy grid mapping
3. LIDAR-camera fusion for autonomous driving

### Evidental Framwork for sensor fusion

- the goal is to know, at every momoet, wheather a location in the perceived environment (a cell of a grid) can be passed though by an autonomous vehicle.
- A corresponding frame of discernment $\Omega$ is defined as { $ \mathbf{D, ND } $ } 
  ($\mathbf{D}$ denotes Drivable Area while $\mathbf{ND}$ donotes Non-Drivable Area) and $ \mathbf{2^S}= \left\{ \emptyset, D, ND, \mathbf{\Omega}\right\} $
-  $\emptyset$ indicates that te cell is note in a state that corrsponds to te mode while $ \Omega $ indicates that the state of the cell is unknown 

### Terms

- discernmet : the ability to judge people andthings well
- power set : the power set of any set $ \mathbf{S} $ is the set all subsets of $ \mathbf{S} $, including empty set and $ \mathbf{S} $ itself, variously denoted as $ \mathbf{P(S)}$ (or $ 2^S$  When the number of elements of $ \mathbf{S} $ is two)













