# GATr_arteries_classification

---


In this repository, the architecture known as the Geometric Algebra Transformer is implemented. In particular, the model will be able to process data simulating two types of 3D arteries: single arteries with stenosis and bifurcated arteries. The peculiarity of GATr is that they are invariant to Euclidean transformations in R3 such as translations, rotations and reflections. As can be seen from the [Report](https://github.com/msilver22/GATr_arteries_classification/blob/main/report.pdf) and the [Presentation](https://github.com/msilver22/GATr_arteries_classification/blob/main/GATr_Sapienza_Presentation.pdf), we implemented them GATr with a light weight attention approach and compared it with the baseline Transformer. 

An overview of the gatr model is given by the following image.
![Architecture](https://github.com/msilver22/GATr_arteries_classification/blob/main/photos/gatr_architecture2.png)
