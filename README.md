# An aggregate of works in computer vision for fire detection.

# Methods

| Author          | Paper | Method                                                 | Own Dataset | Link                                                                |
|-----------------|-------|--------------------------------------------------------|-------------|---------------------------------------------------------------------|
| Dunnings et al. | Yes   | Deep CNN classification (InceptionV3) + superpix. loc. | Yes         | https://github.com/tobybreckon/fire-detection-cnn                   |
| hojak99         | No    | background substraction + red channel rule             | No          | https://github.com/hojak99/fire-detection                           |
|                 |       |                                                        | Yes         | https://github.com/cair/Fire-Detection-Image-Dataset                |
| Steffens et al. | Yes   | Deep CNN classification (InceptionV3)                  | Yes         | https://github.com/steffensbola/furg-fire-dataset                   |
|                 |       | Deep CNN classification (custom arch) + Raspberry Pi   | Yes         | https://github.com/arpit-jadon                                      |
| Foggia et al.   |       | Color + Shape + Motion Features                        |             | https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7014233        |
| Zhang et al.    |       | Deep CNN detection (R-CNN)                             | Synthetic   | https://www.sciencedirect.com/science/article/pii/S1877705817362574 |
|                 |       |                                                        |             |                                                                     |

# Datasets

| Dataset                   | Samples | Annotations | Link                                                                            |
|---------------------------|---------|-------------|---------------------------------------------------------------------------------|
| Foggia et al.             |         | Per-video   | https://mivia.unisa.it/datasets/video-analysis-datasets/fire-detection-dataset/ |
| Aligarh Muslim University |         |             | https://drive.google.com/drive/folders/1HznoBFEd6yjaLFlSmkUGARwCUzzG4whq        |
| Dunnings, Breckon         |         |             | https://collections.durham.ac.uk/downloads/r2d217qp536                          |
| VisiFire                  |         |             | http://signal.ee.bilkent.edu.tr/VisiFire/                                       |

# Applications

| Application             | Platform | Code                                                     |
|-------------------------|----------|----------------------------------------------------------|
| AR Drone Fire Detection | AR Drone | https://github.com/Sanderi44/AR-Drone-Fire-Detection.git |