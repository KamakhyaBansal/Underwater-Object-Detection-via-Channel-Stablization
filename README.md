Underwater-Object-Detection-via-Channel-Stablization
The complex marine environment exacerbates the hallenges of object detection manifold. With the advent of themodern era, marine trash presents a danger to the aquaticecosystem, and it has always been challenging to address thisissue with complete grip. Therefore, there is a significant needto precisely detect marine deposits and locate them accuratelyin challenging aquatic surroundings. To ensure the safety ofthe marine environment caused by waste, the deploy-ment ofunderwater object detection is a crucial tool to mitigate theharm of such waste. Our work explains the image enhancementstrategies used experiments exploring the best detectionobtained after applying these methods. Specifically, we evaluateDetectron 2’s backbones performance using different base models and configurations for the underwater detection task.We first propose a channel stabilization technique on top ofa simplified image enhancement model  help reduce haze and colour cast in training images. The proposed procedure showsimproved results on multi-scale size objects present in the dataset. After processing the images, we explore various backbonesin Detectron2 to give the best detection accuracy for theseimages. In addition, we use a sharpening filter with augmentationtechniques. This highlights the profile of the object which helps usrecognize it easily. We demonstrate our results by verifying theseon TrashCan Data set, both instance and material version.We then explore the best-performing backbone method for thissetting. We apply our channel stabilization and augmentationmethods to the best-performing technique. We also compare ouretection results from Detectron2 using the best backbones withthose from Deformable Transformer. The detection result forsmall size objects in the Instance-version of TrashCan 1.0 gives us a9.53\% absolute increase, in average precision while for the boundingbox we get the absolute gain of 7\% comparedto the baseline. 
## Channel Stablizaition method
## Using simplified RGHS method
## Using Detectron2 for Comparison
