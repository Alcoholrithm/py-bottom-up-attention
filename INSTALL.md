### Requirements
- Linux or macOS with Python ≥ 3.6
- PyTorch ≥ 1.4
- [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch installation.
  You can install them together at [pytorch.org](https://pytorch.org) to make sure of this.
- [pycocotools](https://github.com/cocodataset/cocoapi). Install it by `pip install pycocotools>=2.0.1`.
- OpenCV, optional, needed by demo and visualization


### Build Detectron2 from Source

gcc & g++ ≥ 5 are required. [ninja](https://ninja-build.org/) is recommended for faster build.
After having them, run:
```
python setup.py build develop
