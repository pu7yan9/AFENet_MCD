Adversarial Feature Equilibrium Network for Multimodal Change Detection in Heterogeneous Remote Sensing Images
# AFENet_MCD

<p align="center">
  <img src="AFENet.png" width="100%">
</p>

This is a PyTorch/GPU implementation of the paper [Adversarial Feature Equilibrium Network for Multimodal Change Detection in Heterogeneous Remote Sensing Images](https://ieeexplore.ieee.org/document/10716673):

```
@ARTICLE{pu2024adversarial,
  author={Pu, Yan and Gong, Maoguo and Liu, Tongfei and Zhang, Mingyang and Gao, Tianqi and Jiang, Fenlong and Hu, Xiaobo},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Adversarial Feature Equilibrium Network for Multimodal Change Detection in Heterogeneous Remote Sensing Images}, 
  year={2024},
  volume={62},
  number={},
  pages={1-17},
```

## Requirements

 - [ ] python  3.7.16
 - [ ] torch  1.13.1
 - [ ] torchvision  0.14.1
 - [ ] opencv  4.7.0.72
 - [ ] numpy  1.21.5
 - [ ] pandas  1.3.5

### Dataset

| Multimodal Dataset   | Download Link                                                                                         | Source                                                                             |
|----------------------|-------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| MT-Wuhan             | [Download](https://drive.google.com/file/d/1lNKmvO3VY5wOB6yWqBY6tbUid613yfpS/view?usp=drive_link)     | [Paper](https://www.sciencedirect.com/science/article/pii/S0303243422000952)       |
| MT-HTCD              | [Download](https://drive.google.com/file/d/1CKvBX8gkOdrv-n_EVRTt379bqbGZ3svR/view?usp=drive_link)     | [Paper](https://www.mdpi.com/2072-4292/13/18/3750)                                 |

### Installation

For convenience, our pre-trained models can be downloaded directly here:

| Model                                                                                                 | Dataset      | F1-Score    | Params      | 
|-------------------------------------------------------------------------------------------------------|--------------|-------------|-------------|
| [G_model](https://drive.google.com/file/d/1Q4-YJUEQAMgqy3FfQak-3VPsHSe5N1_f/view?usp=sharing)         | MT-Wuhan     | 60.03       | 297.8M      |
| [D_model](https://drive.google.com/file/d/1eMEVYUmj_0mQdr07SBqrPzBXC-vdEjd5/view?usp=sharing)         | MT-Wuhan     | 60.03       | 11.7M       |
| [G_model](https://drive.google.com/file/d/1QSOa3XDnzjru9tCgBdSzDTRe7nuh6dWm/view?usp=sharing)         | MT-HTCD      | 97.15       | 297.8M      |
| [D_model](https://drive.google.com/file/d/1SixiniihgLnk6G0Bv3ywtLO5h0amAgBu/view?usp=sharing)         | MT-HTCD      | 97.15       | 11.7M       |


## Usage

### Train and Test
```python
  python main.py
```
