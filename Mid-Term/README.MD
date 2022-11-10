## Applied AI_midterm_exam
Midterm exam is going to be based on building a real-time Mask R-CNN using Detectron.
You can use either computer-installed webcam or a consumer graded one for capturing the vide stream.
The task is to implement a simple solution to run Detectron Mask R-CNN algorithm for object detection and instance segmentation with webcam.

### Runtime Requirements are as follows: 
• Installing Detectron 
• CUDA 8 and above 
• cuDNN 6 and above 
• OpenCV 3.4 

### Basic step overview : 

- Installing the detectron on Google Colab
- Using code snippets for accessing to webcam on google colab (this part uses some JavaScript, however the code snippet is available and there is no need for writing your own JS code)
- Inferencing images read from the webcam using detectron and Mask-RCNN.
- Displaying the images in a streaming fashion.

**All the steps are explained in details one by one in the notebook for convenience. Please follow those instructions to get the desired results**

Please note that based on your type of subscription for Google Colab and/or the type of machine that you are using, the speed of inferencing would change.

The final output should be a streaming video, each frame looking something like the following image:

![mask_rcnn](https://user-images.githubusercontent.com/89472694/201169046-921a0b95-b5a7-4555-82ed-702a60782a03.jpg)

--------------------------

*Shout out to "Detectron2 Team" (https://github.com/facebookresearch/detectron2) for the great repository*

*Thanks to "The AI Guy" for sharing a great tutorial for accessing webcam on colab (https://www.youtube.com/watch?v=YjWh7QvVH60)*
