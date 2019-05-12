# Using Photorealistic Face Synthesis and Domain Adaptation to Improve Facial Expression Analysis
This repository includes the training and testing codes for: "Using Photorealistic Face Synthesis and Domain Adaptation to Improve Facial Expression Analysis".

### Dependencies
- [Python2.7](https://www.anaconda.com/download/#linux)
- [PyTorch](http://pytorch.org/)
- [torchvision](http://pytorch.org/docs/master/torchvision)
- [OpenCV](https://opencv.org/)
- [Dlib](http://dlib.net/)

### Datasets
- [The Binghamton University 3D Facial Expression Database (BU-3DFE)](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
- [The Radboud Faces Database (RaFD)](http://www.socsci.ru.nl:8180/RaFD2/RaFD?p=main)
- [The MUG dataset](https://mug.ee.auth.gr/fed/)
- [Oulu-CASIA VIS](http://www.cse.oulu.fi/CMV/Downloads/Oulu-CASIA)

## Usage:

### Clone the repository
```
$ git clone https://github.com/BehzadBozorgtabar/FSDA.git
cd master
```
### Train
```
python synthesis.py --mode='train'
```
### Test
```
python synthesis.py --mode='test'
```
### Face Synthesis Model

![](https://github.com/BehzadBozorgtabar/FSDA/blob/master/main.png)






