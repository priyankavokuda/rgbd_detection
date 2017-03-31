# rgbd_detection

RGB-D detection pipeline with object proposals by EdgeBoxes and object classification by Multimodal CNN.

In this work, object proposal generation is based on Structured Random Forests (SRF) in Edge Boxes and Object Classification is based on the state-of-the- art Convolutional Neural Networks (CNNs). The performance of the combined pipeline is evaluated on the Berkeley 3-D Object Dataset (B3DO) indoor objects dataset. For object detection, we compare favorably against a state-of- the-art method You Only Look Once (YOLO) by ∼7 % points. In addition, we explore the contribution of various imaging modalities on object detection. To this end, we evaluate the influence of additional depth data on both object proposal and classification stages. We show that while additional depth information improves the proposals stage at parsimonious operating points, it results in a modest improvement on the classification stage.


