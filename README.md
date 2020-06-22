<h1 align="center">Face Mask Detection</h1>

<div align= "center">
  <h4>Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>
</div>


## Working
Open terminal. Go into the cloned project directory folder and type the following command:

```$ python3 train_mask_detector.py --dataset dataset```

Now detect the face masks in images

```$ python3 detect_mask_image.py --image images/pic1.jpeg```

Detection in real-time video streams

```$ python3 detect_mask_video.py ```


## Results
94% accuracy for Face Mask Detection after training via tensorflow-gpu==2.0.0(Google colabs)

### Further Enhancements 
 To develope a project which is a door lock system, which opens only when the camera detects that user is wearing a mask.
