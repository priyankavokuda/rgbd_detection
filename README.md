# Object detection using RGB-D data

RGB-D detection pipeline with object proposals by EdgeBoxes and object classification by Multimodal CNN.

This was a research and development project done as part of Masters curriculum.

In this project, object detection is performed on open source datasets which containes the images captured from Kinect in a cluttered scenes. Object detection is performed as a combination of object proposal generation (locating object) and object classification (recognizing object) steps. 

Object Proposal generation is based on Structured Random Forests (SRF) in Edge Boxes and Object Classification is based on the state-of-the- art Convolutional Neural Networks (CNNs). 

The performance of the combined pipeline is evaluated on the Berkeley 3-D Object Dataset (B3DO) indoor objects dataset. Object detection compares favorably against a state-of- the-art method: You Only Look Once (YOLO) by ∼7 % points. 

In addition, the contribution of various imaging modalities on object detection is explored by evaluating the influence of additional depth data on both object proposal and classification stages. 

While additional depth information improves the proposals stage at parsimonious operating points, it results in a modest improvement on the classification stage.

This figure shows our pipeline:
![](https://github.com/priyankavokuda/rgbd_detection/blob/master/images/pipeline.png)


The extracts of the program files are shared here.

This figure shows results generated using YOLO for B3DO dataset.
![](https://github.com/priyankavokuda/rgbd_detection/blob/master/images/result.png)


