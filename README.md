
# GloNets: Globally Connected Neural Networks

<p float="left">
  <img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-fc.jpg" width="48%" />
  <img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-tunable.png" width="48%" /> 
</p>

## Abstract
GloNets introduces a novel neural network architecture that surpasses depth-related limitations of existing deep learning structures. Differing from architectures like ResNet, GloNets ensure stable training and uniform information distribution across all network layers. This allows for superimposing GloNets on any model to enhance depth without increasing complexity or reducing performance.
  
## Repository Contents
`\Code\PyTorch`: Implementation of GloNet in various configurations:
- `GloNet+fc`: GloNet applied to fully connected networks.
- `GloNet+CNN`: GloNet integration with Convolutional Neural Networks.
- `GloNet+ViT`: GloNet combined with Vision Transformers.

`\Images`: Contains images demonstrating GloNet's architecture and its post-learning tunable precision.

## GloNet Speed
<div style="text-align: center;">
<img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-speed.jpg" width="50%" height="50%">
</div>
GloNet, while maintaining comparable performance levels, operates significantly faster than ResNetv2. This is primarily because GloNet does not require Batch Normalization, resulting in enhanced processing speed.


```
## Citation
If you use this work in your research, please cite:
Di Cecco, A., Metta, C., Fantozzi, M., Morandin, F., Parton, M. (2023). GloNets: Globally Connected Neural Networks. arXiv preprint arXiv:2311.15947.
[Link to the preprint](https://arxiv.org/abs/2311.15947)

Presented at the [IDA 2024 Conference](https://ida2024.blogs.dsv.su.se).
```

## License
This project is licensed under the MIT License.

## Contact
For further information or collaboration opportunities, please contact: ant.dicecco@gmail.com


## Acknowledgments
Acknowledgments to those who, with their work, inspired this project, e.g. Yoshua Bengio and Simone Scardapane.
