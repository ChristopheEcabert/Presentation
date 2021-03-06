# Reading Group Presentation

Concept, presentations of 15-30 minutes about different topics on *Machine Learning*, *Computer Vision* mainly focussed on Deep Learning Algorithms.

## Deep Residual Learning for Image Recognition

Microsoft Research [article](https://arxiv.org/abs/1512.03385) on Residual Network Architecture for Image Recognition.

*Deeper neural networks are more difficult to train. We present a residual learning framework to ease the training of networks that are substantially deeper than those used previously. We explicitly reformulate the layers as learning residual functions with reference to the layer inputs, instead of learning unreferenced functions. We provide comprehensive empirical evidence showing that these residual networks are easier to optimize, and can gain accuracy from considerably increased depth. On the ImageNet dataset we evaluate residual nets with a depth of up to 152 layers---8x deeper than VGG nets but still having lower complexity. An ensemble of these residual nets achieves 3.57% error on the ImageNet test set. This result won the 1st place on the ILSVRC 2015 classification task. We also present analysis on CIFAR-10 with 100 and 1000 layers.* 
*The depth of representations is of central importance for many visual recognition tasks. Solely due to our extremely deep representations, we obtain a 28% relative improvement on the COCO object detection dataset. Deep residual nets are foundations of our submissions to ILSVRC & COCO 2015 competitions, where we also won the 1st places on the tasks of ImageNet detection, ImageNet localization, COCO detection, and COCO segmentation.*

[ResNet presentation](ResNet/resnet_presentation.html)

## Faster R-CNN : Towards Real-Time Object Detection with Region Proposal Networks 		

[Faster R-CNN article](https://arxiv.org/pdf/1506.01497.pdf)

*State-of-the-art object detection networks depend on region proposal algorithms to hypothesize object locations. Advances like SPPnet and Fast R-CNN have reduced the running time of these detection networks, exposing region proposal computation as a bottleneck. In this work, we introduce a Region Proposal Network (RPN) that shares full-image convolutional features with the detection network, thus enabling nearly cost-free region proposals. An RPN is a fully convolutional network that simultaneously predicts object bounds and objectness scores at each position. The RPN is trained end-to-end to generate high-quality region proposals, which are used by Fast R-CNN for detection. We further merge RPN and Fast R-CNN into a single network by sharing their convolutional features---using the recently popular terminology of neural networks with 'attention' mechanisms, the RPN component tells the unified network where to look. For the very deep VGG-16 model, our detection system has a frame rate of 5fps (including all steps) on a GPU, while achieving state-of-the-art object detection accuracy on PASCAL VOC 2007, 2012, and MS COCO datasets with only 300 proposals per image. In ILSVRC and COCO 2015 competitions, Faster R-CNN and RPN are the foundations of the 1st-place winning entries in several tracks. Code has been made publicly available.*

[Faster R-CNN presentation](FasterRCNN/fasterrcnn_presentation.html)

##  Image Style Transfer Using Convolutional Neural Networks

[Image Style Transfer article](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)

*Rendering the semantic content of an image in different styles is a difficult image processing task. Arguably, a major limiting factor for previous approaches has been the lack of image representations that explicitly represent semantic information and, thus, allow to separate image content from style. Here we use image representations derived from Convolutional Neural Networks optimised for object recognition, which make high level image information explicit. We introduce A Neural Algorithm of Artistic Style that can separate and recombine the image content and style of natural images. The algorithm allows us to produce new images of high perceptual quality that combine the content of an arbitrary photograph with the appearance of numerous well-known artworks. Our results provide new insights into the deep image representations learned by Convolutional Neural Networks and demonstrate their potential for high level image synthesis and manipulation.*

[Image Style Transfer presentation](ImageStyleTransfer/image_style_transfer.html)

## DeepPose: Human Pose Estimation via Deep Neural Networks

[DeepPose article](https://arxiv.org/abs/1312.4659)

*We propose a method for human pose estimation based on Deep Neural Networks (DNNs). The pose estimation is formulated as a DNN-based regression problem towards body joints. We present a cascade of such DNN regressors which results in high precision pose estimates. The approach has the advantage of reasoning about pose in a holistic fashion and has a simple but yet powerful formulation which capitalizes on recent advances in Deep Learning. We present a detailed empirical analysis with state-of-art or better performance on four academic benchmarks of diverse real-world images*

[DeepPose presentation](DeepPose/deep_pose.html)

## Finding Tiny Faces

[Finding Tiny Faces articles](https://arxiv.org/abs/1612.04402)

*Though tremendous strides have been made in object recognition, one of the remaining open challenges is detecting small objects. We explore three aspects of the problem in the context of finding small faces: the role of scale invariance, image resolution, and contextual reasoning. While most recognition approaches aim to be scale-invariant, the cues for recognizing a 3px tall face are fundamentally different than those for recognizing a 300px tall face. We take a different approach and train separate detectors for different scales. To maintain efficiency, detectors are trained in a multi-task fashion: they make use of features extracted from multiple layers of single (deep) feature hierarchy. While training detectors for large objects is straightforward, the crucial challenge remains training detectors for small objects. We show that context is crucial, and define templates that make use of massively-large receptive fields (where 99% of the template extends beyond the object of interest). Finally, we explore the role of scale in pre-trained deep networks, providing ways to extrapolate networks tuned for limited scales to rather extreme ranges. We demonstrate state-of-the-art results on massively-benchmarked face datasets (FDDB and WIDER FACE). In particular, when compared to prior art on WIDER FACE, our results reduce error by a factor of 2 (our models produce an AP of 82% while prior art ranges from 29-64%).*

[Finding Tiny Faces presentation](TinyFace/tiny_face.html)

## 3D Face Morphable Models "In-The-Wild"

[3D Face Morphable Models "In-The-Wild"](https://arxiv.org/pdf/1701.05360.pdf)

*3D Morphable Models (3DMMs) are powerful statistical models of 3D facial shape and texture, and among the state-of-the-art methods for reconstructing facial shape from single images. With the advent of new 3D sensors, many 3D facial datasets have been collected containing both neutral as well as expressive faces. However, all datasets are captured under controlled conditions. Thus, even though powerful 3D facial shape models can be learnt from such data, it is difficult to build statistical texture models that are sufficient to reconstruct faces captured in unconstrained conditions (“in-the-wild”). In this paper, we propose the first, to the best of our knowledge, “in-the-wild” 3DMM by combining a powerful statistical model of facial shape, which describes both identity and expression, with an “in-the-wild” texture model. We show that the employment of such an “in-the-wild” texture model greatly simplifies the fitting procedure, because there is no need to optimize with regards to the illumination parameters. Furthermore, we propose a new fast algorithm for fitting the 3DMM in arbitrary images. Finally, we have captured the first 3D facial database with relatively unconstrained conditions and report quantitative evaluations with state-of-the-art performance. Complementary qualitative reconstruction results are demonstrated on standard “in-the-wild” facial databases. An open source implementation of our technique is released as part of the Menpo Project.*

[3D Face Morphable Models "In-The-Wild" Presentation](MMInTheWild/mm_in_the_wild_presentation.html)

## Learning from Simulated and Unsupervised Images through Adversarial Training

[Learning from Simulated and Unsupervised Images through Adversarial Training](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shrivastava_Learning_From_Simulated_CVPR_2017_paper.pdf)

*With recent progress in graphics, it has become more tractable to train models on synthetic images, poten-*
*tially avoiding the need for expensive annotations. However, learning from synthetic images may not achieve the desired performance due to a gap between synthetic and real image distributions. To reduce this gap, we propose Simulated+Unsupervised (S+U) learning, where the task is to learn a model to improve the realism of a simulator’s output using unlabeled real data, while preserving the annotation information from the simulator. We develop a method for S+U learning that uses an adversarial network similar to Generative Adversarial Networks (GANs), but with synthetic images as inputs instead of random vectors. We make several key modifications to the standard GAN algorithm to preserve annotations, avoid artifacts, and stabilize training: (i) a ‘self-regularization’ term, (ii) a local adversarial loss, and (iii) updating the discriminator using a history of refined images. We show that this enables generation of highly realistic images, which we demonstrate both qualitatively and with a user study. We quantitatively evaluate the generated images by training models for gaze estimation and hand pose estimation. We show a significant improvement over using synthetic images, and achieve state-of-the-art results on the MPIIGaze dataset without any labeled real data.*

[Learning from Simulated and Unsupervised Images through Adversarial Training Presentation](SimulatedUnsupervisedImage/simulated_unsupervised_image.html)

# 	MoFA: Model-based Deep Convolutional Face Autoencoder for Unsupervised Monocular Reconstruction


[MoFA: Model-based Deep Convolutional Face Autoencoder for Unsupervised Monocular Reconstruction](https://arxiv.org/pdf/1703.10580.pdf)


*In this work we propose a novel model-based deep convolutional autoencoder that addresses the highly challenging problem of reconstructing a 3D human face from a single in-the-wild color image. To this end, we combine a convolutional encoder network with an expert-designed generative model that serves as decoder. The core innovation is the differentiable parametric decoder that encapsulates image formation analytically based on a generative model. Our decoder takes as input a code vector with exactly defined semantic meaning that encodes detailed face pose, shape, expression, skin reflectance and scene illumination. Due to this new way of combining CNN-based with model-based face reconstruction, the CNN-based encoder learns to extract semantically meaningful parameters from a single monocular input image. For the first time, a CNN encoder and an expert-designed generative model can be trained end-to-end in an unsupervised manner, which renders training on very large (unlabeled) real world data feasible. The obtained reconstructions compare favorably to current state-of-the-art approaches in terms of quality and richness of representation.*

[MoFA: Model-based Deep Convolutional Face Autoencoder for Unsupervised Monocular Reconstruction - Presentation](mofa/mofa.html) 

# Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric CNN Regression

[Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric CNN Regression](https://arxiv.org/abs/1703.07834)

3D face reconstruction is a fundamental Computer Vi-sion problem of extraordinary difficulty. Current systems often assume the availability of multiple facial images (some-times from the same subject) as input, and must addressa number of methodological challenges such as establish-ing dense correspondences across large facial poses, expressions, and non-uniform illumination. In general these methods require complex and inefficient pipelines for modelbuilding and fitting. In this work, we propose to address many of these limitations by training a Convolutional Neural Network (CNN) on an appropriate dataset consisting of 2D images and 3D facial models or scans. Our CNN works with just a single 2D facial image, does not require accurate alignment nor establishes dense correspondence between images, works for arbitrary facial poses and expressions,and can be used to reconstruct the whole 3D facial geometry (including the non-visible parts of the face) bypassing the construction (during training) and fitting (during testing) of a 3D Morphable Model. We achieve this via a simple CNN architecture that performs direct regression of a volumetric representation of the 3D facial geometry from a single 2D image. We also demonstrate how the related task of facial landmark localization can be incorporated into the proposed framework and help improve reconstruction quality, especially for the cases of large poses and facial expressions. Code and models will be made available at http://aaronsplace.co.uk

[Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric CNN Regression - Presentation](LargePoseFaceReconstruction/LargePoseFaceReconstruction.html)

# CentralNet: a Multilayer Approach for Multimodal Fusion

[CentralNet: a Multilayer Approach for Multimodal Fusion](https://arxiv.org/pdf/1808.07275.pdf)

This paper proposes a novel multimodal fusion approach, aiming to produce best possible decisions by integrating information coming from multiple media. While most of the past multimodal ap- proaches either work by projecting the features of different modalities into the same space, or by coordinating the representations of each modality through the use of constraints, our approach borrows from both visions. More specifically, assuming each modality can be processed by a separated deep convolutional network, allowing to take decisions in- dependently from each modality, we introduce a central network linking the modality specific networks. This central network not only provides a common feature embedding but also regularizes the modality specific networks through the use of multi-task learning. The proposed approach is validated on 4 different computer vision tasks on which it consistently improves the accuracy of existing multimodal fusion approaches. 

[CentralNet: a Multilayer Approach for Multimodal Fusion - Presentation](CentralNet/central_net.html)