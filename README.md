# CityscapesSemSegSanFranciscoMarina
Training in Cityscapes dataset, implement semantic segmentation to detect objects like cars, pedestrians, bicycles, stop signs, 
and traffic lights for better scenic understanding. 

In semantic segmentation, each object is painted with tiny pixels that make up a computer image that belong to that classes of object. Each class of object has a unique color identification. For example, pedestrians are painted red, sky is painted light blue, cars are painted navy blue, sidewalk is painted pink, buildings are painted gray, roads are painted purple, and trees are painted green.

The image files are located in segmentedImgs directory.

Generated semantic segmentation videoes for the first time.  I will improve on the  training of the Cityscapes dataset.

From my observation, the road is being classified best when the road is tilted on one side and the road is bumpy with surface texture.
It also do well when the car is making a turn. It does very poor on roads with flat surface. On my next video recording, I will try to point the camera more downward to focus on the road surface more. I think my camera is pointing too much at an upward angle. Therefore, it is hard for road classification.

Another observation is that as I calibrate the camera images and undistort each video frame. There is a huge performance improvement in road classification. More areas of the road is painted purple than before.

I will train the dataset more until the entropy loss is going down a little more.

Here is the youtube link:

https://youtu.be/wCZ7FdB50ew

https://youtu.be/BfEhLJNSnTM
