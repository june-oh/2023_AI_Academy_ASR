# 2023 AI Academy ASR

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![nVIDIA](https://img.shields.io/badge/nVIDIA-%2376B900.svg?style=for-the-badge&logo=nVIDIA&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

> 딥러닝을 이용한 음성인식 기초 실습

### 0. Tutorial
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/0_tutorial.ipynb" ><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Tutorial for python and data science packages
- python review
- numpy
- matplotlib

### 1. Audio file handling
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/1_Audio_file_handling_using_torchaudio.ipynb" ><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Audio file handling using torchaudio
- Load audio file(torchaudio.load)
- Feature extraction(Mel-spectrogram, MFCC)

### 3. Audio Classification using MLP
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/3_Audio_Classification_using_MLP.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Audio MNIST classification using MLP(torch.Linear)

### 4. CTC
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/4_CTC.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Simple Exercise(model training using CTC loss) for Connectionist Temoral Classification 

### 5. Whisper
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/5_whisper.ipynb" ><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Exercise using OpenAI - Whisper and Gradio

### 6. E2E ASR model finetune with Nemo
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/6_nemo_finetuning.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Quartznet Model finetune with Nemo(English to Korean)

### 7. WFST 
<a href="https://colab.research.google.com/github/june-oh/2023_AI_Academy_ASR/blob/main/7_WFST.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Exercise for WFST using k2
- C,L,G transducer
- composition, determinization

## Libraries
- `PyTorch` : [pytorch/pytorch]( https://github.com/pytorch/pytorch )
- `NeMo` : [Nvidia/NeMo](https://github.com/NVIDIA/NeMo)
- `TorchAudio` : [pytorch/audio](https://github.com/pytorch/audio) 
- `NumPy` : [numpy/numpy](https://github.com/numpy/numpy)
- `matplotlib` :[matplotlib/matplotlib](https://github.com/matplotlib/matplotlib)
- `Whisper` : [openai/whisper](https://github.com/openai/whisper)
- `gradio` : [gradio-app/gradio](https://github.com/gradio-app/gradio)
