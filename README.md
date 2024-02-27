# ConvNeXt for Image Captioning

<!-- ABOUT THE PROJECT -->
## About the project

This study explores the effectiveness of the ConvNeXt model, an advanced computer vision architecture, in the task of image captioning. We integrated ConvNeXt with a Long Short-Term Memory network that includes a visual attention module, focusing on assessing its performance across different scenarios. Experiments were conducted using various ConvNeXt versions for feature extraction, different learning rates during the training phase were tested, and the impact of including or excluding teacher-forcing was analyzed. The MS COCO 2014 dataset was employed, with top-5 accuracy and BLEU metrics used to evaluate performance. The implementation of ConvNeXt in image captioning systems reveals notable performance enhancements. In terms of BLEU-4 scores, ConvNeXt outperformed existing benchmarks by 43.04% for models using soft-attention and by 39.04% for those with hard-attention mechanisms. Furthermore, ConvNeXt surpassed models based on vision transformers and data-efficient image transformers by 4.57% and 0.93%, respectively, in BLEU-4 scores. When compared with systems using encoders such as ResNet-101, ResNet-152, VGG-16, ResNeXt-101, and MobileNet V3, ConvNeXt achieved higher top-5 accuracy improvements of 6.44%, 6.46%, 6.47%, 6.39%, and 6.68%, and reduced loss by 18.46%, 18.44%, 18.46%, 18.24%, and 18.72%, respectively.

### Paper

[https://ieeexplore.ieee.org/abstract/document/10311597](https://ieeexplore.ieee.org/document/10410861)

### Built With

* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)
* [Hugging Face](https://huggingface.co/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/ConvNeXt-for-Image-Captioning.git

## Description of the main files

- [train.py](https://github.com/Leo-Thomas/ConvNeXt-for-Image-Captioning-/blob/main/train.py): Network training script. 
- [caption.py](https://github.com/Leo-Thomas/ConvNeXt-for-Image-Captioning-/blob/main/caption.py): Used to perform the inference process for an input image.
- [models.py](https://github.com/Leo-Thomas/ConvNeXt-for-Image-Captioning-/blob/main/models.py): It contains the whole architecture including the encoder and decoder components.

## Data set

We used the 2014 version of the COCO dataset. It can be found for free in the official web site and includes the [training](http://images.cocodataset.org/zips/train2014.zip) and [validation](http://images.cocodataset.org/zips/val2014.zip) sub data sets.

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CITAITON -->
## Citation

@ARTICLE{10410861,
  author={Ramos, Leo and Casas, Edmundo and Romero, Cristian and Rivas-Echeverría, Francklin and Morocho-Cayamcela, Manuel Eugenio},
  journal={IEEE Access}, 
  title={A Study of ConvNeXt Architectures for Enhanced Image Captioning}, 
  year={2024},
  volume={12},
  number={},
  pages={13711-13728},
  doi={10.1109/ACCESS.2024.3356551}}

<!-- CONTACT -->
## Contact

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - leo.ramos@kauel.com

Francklin Rivas - [LinkedIn](https://www.linkedin.com/in/francklin-rivas-echeverria-514180144/) - frivas@yachaytech.edu.ec

Eugenio Morocho - [LinkedIn](https://www.linkedin.com/in/eugenio-morocho-cayamcela/) - mmorocho@yachaytech.edu.ec




<p align="right">(<a href="#top">back to top</a>)</p>
