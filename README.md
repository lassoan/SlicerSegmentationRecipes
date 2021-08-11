# Segmentation recipes for 3D Slicer

Recipes for solving common image segmentation tasks using [3D Slicer](https://www.slicer.org).
- [Skin surface extraction](SkinSurface2/README.md)
- [Craniotomy (splitting segments)](Craniotomy/README.md)
- [Merge segments](MergeSegments/README.md)
- [Aorta segmentation (fast, using Fast marching)](AortaFastMarching/README.md)
- [Aorta segmentation (high-accuracy, using Grow from seeds)](AortaMaskedGrowFromSeeds/README.md)
- [Cerebral vessel segmentation by subtraction](VesselSegmentationBySubtraction/README.md)
- [Segmentation on arbitrarily oriented slices](ObliqueSliceSegmentation/README.md)
- [Skull stripping (keep brain region and remove skull bone and soft tissues) on CT](CTSkullStripping/README.md)

External links:
- Whole heart segmentation from CTA:
  - [Video tutorial by Andras Lasso](https://youtu.be/BJoIexIvtGo)
  - [Video tutorial by Justin Cramer](https://youtu.be/55cqpl8_b8c)
- Spine segmentation from CT:
  - [Video tutorial and slides: Spine segmentation from CT and combining with 3D models](https://www.slicer.org/wiki/Documentation/Nightly/Training#Slicer4_Image_Segmentation)
- Femur and pelvis segmentation from CT:
  - [Video tutorial](https://www.slicer.org/wiki/Documentation/Nightly/Training#Slicer4_Image_Segmentation)
- [Segmentation video tutorials from CHU de Rouen (France)](https://www.youtube.com/channel/UC8vxI0-dEWrw0_tBF-v8xGA/videos): many step-by-step segmentation tutorials, including liver, wrist bones, lungs, kidneys, hip, and various animals.
- [Kitware's 3D Slicer segmentation tutorial slides](https://data.kitware.com/#item/5b0f9a308d777f15ebe1fc26)

Obsolete recipes (we have better tools now)
- [Skin surface extraction using region growing](SkinSurface/README.md)
