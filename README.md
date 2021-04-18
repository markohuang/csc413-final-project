## A Comparison Between Music and Voice Recognition
This repository is for the Final Project of CSC413: Neural Networks and Deep Learning. We explore the effectiveness of transfer learning in the audio classification domain. By repurposing a music genre classification model for speaker recognition and vice versa, we show that transfer learning in the audio classification domain might not be as effective for image classification.

### Dataset
[FMA dataset](https://github.com/mdeff/fma): Dataset for Music Genre Classification
[VCTK dataset](https://datashare.ed.ac.uk/handle/10283/3443): Dataset for Speaker Recognition

### Model Architecture
The pre-trained model ([Rawnet](https://github.com/Jungjee/RawNet) and [ConvNet](https://github.com/pushnyakov/WWWMusicalGenreRecognitionChallenge)) architecture are shown below.



![image](https://user-images.githubusercontent.com/29292822/115158691-788f6c00-a05d-11eb-8dcc-8258d5c2deaa.png =800x)

### Code
The following notebooks are used for training and evaluating the Music Genre Classification and Speaker Recognition Tasks
1. ['ConvNet_fma_pytorch.ipynb']: ConvNet model trained on FMA dataset using Pytorch
2. ['ConvNet_vctk_keras.ipynb']: ConvNet model trained on VCTK dataset using Kares
3. ['RawNet_fma.ipynb']: RawNet2 model trained on FMA dataset
4. ['RawNet_vctk.ipynb']: RawNet2 model trained on VCTK dataset

['ConvNet_fma_pytorch.ipynb']: https://github.com/markohuang/csc413-final-project/blob/main/ConvNet_fma_pytorch.ipynb
['ConvNet_vctk_keras.ipynb']: https://github.com/markohuang/csc413-final-project/blob/main/ConvNet_vctk_keras.ipynb
['RawNet_fma.ipynb']: https://github.com/markohuang/csc413-final-project/blob/main/RawNet_fma.ipynb
['RawNet_vctk.ipynb']: https://github.com/markohuang/csc413-final-project/blob/main/RawNet_vctk.ipynb
