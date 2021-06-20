Merging [airsplay/py-bottom-up-attention](https://github.com/airsplay/py-bottom-up-attention) and [faizanahemad/detectron2](https://github.com/faizanahemad/detectron2),
since airsplay's py-bottom-up-attention was running on old detectron2.

## Test Environment
Ubuntu 16.04 LTS
NVIDIA A100-PCIE-40GB
CUDA Version: 11.0
NVIDIA-Driver 450

## Installation

See [INSTALL.md](INSTALL.md).

## License

Detectron2 is released under the [Apache 2.0 license](LICENSE).

## Citing Detectron2

If you use Detectron2 in your research or wish to refer to the baseline results published in the [Model Zoo](MODEL_ZOO.md), please use the following BibTeX entry.

Detectron2:
```BibTeX
@misc{wu2019detectron2,
  author =       {Yuxin Wu and Alexander Kirillov and Francisco Massa and
                  Wan-Yen Lo and Ross Girshick},
  title =        {Detectron2},
  howpublished = {\url{https://github.com/facebookresearch/detectron2}},
  year =         {2019}
}
```

Bottom-up Attention:
```BibTeX
@inproceedings{Anderson2017up-down,
  author = {Peter Anderson and Xiaodong He and Chris Buehler and Damien Teney and Mark Johnson and Stephen Gould and Lei Zhang},
  title = {Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering},
  booktitle={CVPR},
  year = {2018}
}
```

LXMERT:
```BibTeX
@inproceedings{tan2019lxmert,
  title={LXMERT: Learning Cross-Modality Encoder Representations from Transformers},
  author={Tan, Hao and Bansal, Mohit},
  booktitle={Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing},
  year={2019}
}
```
