# CityscapesSemSegSanFranciscoMarina
Training in Cityscapes dataset, implement semantic segmentation to detect objects like cars, pedestrians, bicycles, stop signs, 
and traffic lights for better scenic understanding. 

In semantic segmentation, each object is painted with tiny pixels that make up a computer image that belong to that classes of object. Each class of object has a unique color identification. For example, pedestrians are painted red, sky is painted light blue, cars are painted navy blue, sidewalk is painted pink, buildings are painted gray, roads are painted purple, and trees are painted green.

The image files are located in segmentedImgs directory.

Generated semantic segmentation videoes for the first time.  I will improve on the  training of the Cityscapes dataset.

From my observation, the road is being classified best when the road is tilted on one side and the road is bumpy with surface texture.
It also do well when the car is making a turn. It does very poor on roads with flat surface. On my next video recording, I will try to point the camera more downward to focus on the road surface more. I think my camera is pointing too much at an upward angle. Therefore, it is hard for road classification.

Another observation is that as I calibrate the camera images and undistort each video frame. There is some performance improvement in road classification. 

I will train the dataset more until the entropy loss is going down a little more.

I have a very simple camera.  If I using the videos provided
by Udacity's self-driving car curriculum, the road is painted well in most cases.

Youtube links using videos from Udacity's self-driving car curriculum:
https://youtu.be/6TqYQ3kcgj0

https://youtu.be/o2pcyRc12Vs

https://youtu.be/xa-DvQLKOuI

Here are the youtube links from videos taken frommy camera:

https://youtu.be/wCZ7FdB50ew

https://youtu.be/BfEhLJNSnTM

On 11/16/17, after 8 days of another round of training, the entropy loss has reduced from 0.6 to 0.433. From the augmented images that I generated, the road classification shows improvements. I will generated more videos to see the results tonight.

Here is the youtube link from video taken from my camera, showing improvements over the 1st round of training:

https://youtu.be/wwYClC1BfT0

In the mean time, third round of training is starting, too.

