# OrigamiDetection
Origami Object Detection using YOLOv5

I am testing my knowledge in object detection field by using YOLOv5 and custom dataset.

The dataset i have made from scratch. Taking pictures for objects then labeling them on roboflow website.


## Dataset Origami Information

The dataset contains ~950 image for training, ~100 image for validation, and ~30 image for testing.
The dataset contains 5 classes {Box, Plane, Flower, Shipe, Tea-Plate}
You can find the dataset in the Roboflow website. (Data Link In Roboflow)[https://universe.roboflow.com/alielgamal9/origami]

------------------------------------------------------------------------------------------------------------------------------------------------------

## Results

This results based on training on the v20 of the dataset.



## Questions

The most benefit from this experience is that i got a lot of questions that i need their answers, most of them i could not find their answers by easy searching.

I will list all questions i have until now to find their answers later. The question that i will find it's answer and sure about it by 90%-98%, i will write down it's answer.

1. How many images i need for each object?
  A: not yet

2. Are images need to be from different colors?
  A: if the color is important, then yes. otherwise, preprocess the images to be in grayscale.

3. If the color is important, then do i need to get n images from each color?
  A:

4. Is collecting images process is the most important part in object detection?
  A:

5. Is collecting images process take 80% from the object detection?
  A:

6. what is the best one object per image, multiple objects from same class per image, multiple objects from different classes per images, or mixed? and why?
  A:

7. when to say the data is not good for training?
  A:

8. What if we get images for object in different angles in the same background, then copy the object and put it in different backgrounds to increase our training images without taking more images (this process could be automated which would saving a huge time in collecting images and labeling them). Is that a correct theory or not? and why?
  A:

9. Why not to model the object in any 3d design program and take the pictures (this process could be automated). the needed time would be in modeling or getting the appropriate scene and model the object only. The automation part could have huge features as scalling the object in different sizes without any extra effort from human side. Is that a correct theory or not? and why?
  A:

10. Is the location of the object in the image make a different in the accuracy?Is the object should appear in different locations in all images?why?
  A:
  
I hope i can find the answers for those questions and understand them clearly.
------------------------------------------------------------------------------------------------------------------------------------------------------
