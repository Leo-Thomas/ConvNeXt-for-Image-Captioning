# A ConvNeXt Backbone-based Approach for Image Captioning

<!-- ABOUT THE PROJECT -->
## About the project

This work proposes a ConvNeXt backbone-based model for image captioning. Specifically, we integrate the ConvNeXt convolutional model -a state-of-the-art computer vision architecture- with a long short-term memory network enclosing a visual attention module. Overall, an encoder-decoder architecture capable of generating accurate image captions is proposed and tested. First, we study the impact of using different versions of ConvNeXt for feature extraction, along with different learning rates during the encoder training stage. We have also analyzed the effect of the inclusion and exclusion of teacher-forcing at the decoder. For training, we used the 2014 MS COCO dataset; and for testing, we adopted the top-5 accuracy and BLEU as performance metrics. Simulation results show that our proposal outperforms the benchmark's metrics, as all our models improve the results in terms of BLEU-4. In particular, our leading model surpassed the benchmark by 43.04 % for its soft-attention model and 39.04 % for its hard-attention model. Similarly, our proposal exceeded equivalent approaches based upon vision transformers and data-efficient image transformers by 4.57 % and 0.93 %, respectively. Finally, we proved that our approach surpassed the alternatives that exploit convolutional neural network-based encoders in terms of top-5 accuracy; including ResNet-101, ResNet-152, ResNeXt-101, and MobileNet V3.

This project was developed by Leo Ramos student at [Yachay Tech University](https://www.yachaytech.edu.ec/en/). It was supervised by Eugenio Morocho, Francklin Rivas professors at [Yachay Tech University](https://www.yachaytech.edu.ec/en/), and Edmundo Casas and Cristian Romero from [Kauel](https://kauel.com/#).

### Built With

* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)
* [Hugging Face](https://huggingface.co/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Installation

pip install git+https://github.com/Leo-Thomas/ConvNeXt-for-Image-Captioning-.git

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



<!-- CONTACT -->
## Contact

Francklin Rivas - [LinkedIn](https://www.linkedin.com/in/francklin-rivas-echeverria-514180144/) - frivas@yachaytech.edu.ec

Eugenio Morocho - [LinkedIn](https://www.linkedin.com/in/eugenio-morocho-cayamcela/) - mmorocho@yachaytech.edu.ec

Leo Ramos - [LinkedIn](https://www.linkedin.com/in/leo-thomas-ramos/) - leo.ramos@yachaytech.edu.ec

<br>
<br>

Project link: [https://github.com/Leo-Thomas/A-Knowledge-based-System-for-Assessing-Sustainability-for-SMEs-in-the-Fashion-Industry.git](https://github.com/Leo-Thomas/A-Knowledge-based-System-for-Assessing-Sustainability-for-SMEs-in-the-Fashion-Industry.git)

<p align="right">(<a href="#top">back to top</a>)</p>
