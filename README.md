Replicating # FUnIE-GAN-PyTorch

PyTorch implementations of the [paper](https://arxiv.org/pdf/1903.09766.pdf).

## Tasks

- [x] Data preprocessing
- [x] FUnIE-GAN-V1 architecture trained using paired data
- [x] FUnIE-GAN-V2 architecture trained using paired data
- [x] FUnIE-GAN-UP architecture trained using unpaired data
- [x] Official evaluation
- [x] Provide model weights

## Installation

```shell
pip install --no-cache-dir -r requirements.txt
```

## Data Preprocessing

Please refer to [here](https://github.com/rowantseng/FUnIE-GAN-PyTorch/tree/master/preprocess) to prepare the paired and unpaired dataset.

## Model Architecture

The network architecture `FUnIE-GAN` is tackled with paired dataset training. On the other hand, `FUnIE-GAN-UP` is designed for the unpaired data.



## Citing FUnIE-GAN

```
@article{islam2019fast,
     title={Fast Underwater Image Enhancement for Improved Visual Perception},
     author={Islam, Md Jahidul and Xia, Youya and Sattar, Junaed},
     journal={IEEE Robotics and Automation Letters (RA-L)},
     volume={5},
     number={2},
     pages={3227--3234},
     year={2020},
     publisher={IEEE}
 }
```

## License

The code is released under the [MIT license](https://github.com/rowantseng/FUnIE-GAN-PyTorch/blob/master/LICENSE).
