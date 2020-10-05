Note: Credits are given to Official OpenCV samples along with other articles linked below

# Introduction

Today, image processing and computer vision are literally everywhere. From Space Missions to Self driving cars, from Snapchat to CamScanner in your phone. Anything with a light sensor requires the use of these two.

## Image Processing and Computer Vision

Generally speaking, image processing is all about transforming (processing) the input image file. Typically, it’s done with the usage of specific software, to name just Adobe Photoshop or GIMP. Some of these transformations are done manually (by the graphic, for instance, adding new layers) or automatically (by the built-in algorithm, for example, sharpening).

It is a fundamental skill useful for any field that deals with visual inputs.

One of the most outstanding examples is medicine. Image processing in medicine is used in order to enhance the medical image’s quality and perceptibility. As a result of this image enhancement process, a physician can make a quicker and more accurate diagnosis, simply put, because they see a more clear picture.

On the other hand, Computer vision works entirely differently. Here, nothing happens to the file itself. This is due to the goal, which is to interpret the image and its contents. One of the most significant usages of computer vision is in the motor industry. Computer vision is used here as an assistant for the driver that scans the vehicle’s surroundings and analyzes them for potential threats, obstacles, and other relevant situations .
[ref](https://addepto.com/the-use-of-opencv-in-image-processing-5-examples/)

## What's good about Image Processing?

- Vibrant communities and lots of projects coming up
- Visuals advantage: small efforts big impacts
- Initial learning curve is not steep :)
- Real time advantage: Easy to demo basic prototypes

## Some Primers

We'll get to know some of the basics starting from: 

- **Pixels**
- **Color spaces**
- **Image Transforms**

Then we'll shortly visit:

- Morphology
- Thresholding
- Histograms
- and more

### **Let's get Practical!**

What's in the store?

- Intro on Google Colab

[Google Colaboratory](https://colab.research.google.com/drive/1PZfpFPVFMT_b-Mkyg6t7K2dMKE03_RfK#scrollTo=Tz7UAjxjfMuz)

- Some basic transforms
    - Color Isolation - Pop effect
    - Color functions

- Finding Waldo using Template Matching

    **What is template matching?**

    Template matching is a process where we take the input image and try to slide the target image over the input. This input image is then matched pixel-wise with the target and the closest match will be highlighted.

    Refs 
    [Multiscale Template matching](https://www.pyimagesearch.com/2015/01/26/multi-scale-template-matching-using-python-opencv/)
    [Sliding window](https://www.pyimagesearch.com/2020/06/29/opencv-selective-search-for-object-detection/) 
    [Waldo ref](https://analyticsindiamag.com/my-fun-project-with-opencv-finding-waldo-game/)

- Cam scanner
    - Importance of morphology and thresholding
    - Image Warping
- OMRChecker

**Future directions**

- Speed and Efficiency: do it in C++
- The Classics
    - OCR
    - Object Detection
    - Object Identification
- New ways of inputs
    - like Kinect
    - Smart Home & IOT
- It's a step towards Computer Vision and Machine Learning
    - GANs
    - ConvNets
    - Motion Magnification
    - PoseNets, Deepfakes and what not

**Areas to look into**

- Robotics | Self driving cars | Automations in Manufacturing |
- AR, VR
- More from here:
    - [https://www.qblocks.cloud/creators/computer-vision-google-colab-notebooks](https://www.qblocks.cloud/creators/computer-vision-google-colab-notebooks)

## Resources

Adrian Rosebrock

- [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)

Satya Malik

- [https://www.learnopencv.com/](https://www.learnopencv.com/)
- The Encyclopedia of Tutorials : [https://github.com/spmallick/learnopencv](https://github.com/spmallick/learnopencv)

Official Docs

- [https://docs.opencv.org/master/d6/d00/tutorial_py_root.html](https://docs.opencv.org/master/d6/d00/tutorial_py_root.html)
- [https://docs.opencv.org/4.4.0](https://docs.opencv.org/4.4.0)

Sentdex's Video Tutorials 

- [https://www.youtube.com/watch?v=Z78zbnLlPUA&list=PLQVvvaa0QuDdttJXlLtAJxJetJcqmqlQq&index=1](https://www.youtube.com/watch?v=Z78zbnLlPUA&list=PLQVvvaa0QuDdttJXlLtAJxJetJcqmqlQq&index=1)
- [https://pythonprogramming.net/search/?q=opencv](https://pythonprogramming.net/search/?q=opencv)

More examples 

- [https://github.com/CodecWang/OpenCV-Python-Tutorial](https://github.com/CodecWang/OpenCV-Python-Tutorial)

**Fun stuff to check out** 

- [https://www.learnopencv.com/Funny-Mirrors-Using-OpenCV/](https://www.learnopencv.com/Funny-Mirrors-Using-OpenCV/)
- [https://pythonprogramming.net/open-cv-basics-python-plays-gta-v/](https://pythonprogramming.net/open-cv-basics-python-plays-gta-v/)

**Apps to Try out** 

- Google Lens
- Depth Labs
- Arts & Culture

**More interesting projects**

- [https://github.com/surya-veer/movement-tracking](https://github.com/surya-veer/movement-tracking)
- [https://github.com/arunponnusamy/object-detection-opencv](https://github.com/arunponnusamy/object-detection-opencv)
- [https://github.com/uvipen/QuickDraw](https://github.com/uvipen/QuickDraw)
- [https://www.pyimagesearch.com/2020/09/21/opencv-automatic-license-number-plate-recognition-anpr-with-python/](https://www.pyimagesearch.com/2020/09/21/opencv-automatic-license-number-plate-recognition-anpr-with-python/)