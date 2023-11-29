
# GloNets: Globally Connected Neural Networks

<p float="left">
  <img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-fc.jpg" width="48%" />
  <img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-tunable.png" width="48%" /> 
</p>

## What is GloNet?
[https://arxiv.org/abs/2311.15947](https://arxiv.org/abs/2311.15947) 

GloNets introduces a novel neural network architecture that surpasses depth-related limitations of existing deep learning structures. Unlike architectures such as ResNet, GloNets ensure stable training and uniform information distribution across all network layers. A key feature of GloNets is the use of continuous early exits at every layer, creating a network that can be progressively turned on or off. This flexibility allows for balancing the system's energy requirements. Additionally, as the output is an overlay of networks or elementary basis functions, it lends itself to a new degree of model explainability.

  
## Repository Contents
`\Code\PyTorch`: Implementation of GloNet in various configurations:
- `GloNet+fc`: GloNet applied to fully connected networks.
- `GloNet+CNN`: GloNet integration with Convolutional Neural Networks.
- `GloNet+ViT`: GloNet combined with Vision Transformers.

`\Images`: Contains images demonstrating GloNet's architecture and its post-learning tunable precision.

## GloNet Speed

GloNet, while maintaining comparable performance levels, operates significantly faster than ResNetv2. This is primarily because GloNet does not require Batch Normalization, resulting in enhanced processing speed.
<div style="text-align: center;">
<img src="https://github.com/AntonioDiCecco/GloNet/blob/main/Images/GloNet-speed.jpg" width="50%" height="50%">
</div>



## Citation
If you use this work in your research, please cite:
```
Di Cecco, A., Metta, C., Fantozzi, M., Morandin, F., Parton, M. (2023). GloNets: Globally Connected Neural Networks. arXiv preprint arXiv:2311.15947.
[Link to the preprint](https://arxiv.org/abs/2311.15947)
```

Submitted to the [IDA 2024 Conference](https://ida2024.blogs.dsv.su.se).


## License
This project is licensed under the MIT License.

## Contact
For further information or collaboration opportunities, please contact: ant.dicecco@gmail.com


## Acknowledgments
Acknowledgments to those who, with their work, inspired this project, e.g. Yoshua Bengio and Simone Scardapane.
