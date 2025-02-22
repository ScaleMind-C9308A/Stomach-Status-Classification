# ChromoEndoscopy IMG Research

Normal             |  Abnormal
:-------------------------:|:-------------------------:
![](https://github.com/ScaleMind-C9308A/Stomach-Status-Classification/blob/main/Data%20set/Original%20Form/Train/Group%201%20-%20Normal/CHGastro_Normal_001.png)  |  ![](https://github.com/ScaleMind-C9308A/Stomach-Status-Classification/blob/main/Data%20set/Original%20Form/Train/Group%202%20-%20Abnormal/CHGastro_Abnormal_013.png)

### Git repo cloning

```
git clone https://github.com/ScaleMind-C9308A/Stomach-Status-Classification.git
```

### Environment Information

```
Python==3.9.5
wheel 
pandas==1.4.4
matplotlib==3.6.0
seaborn==0.12.0
deep-forest==0.1.5
scikit-learn==1.1.2
numpy==1.19.5
tensorflow==2.7.0
torch==1.12.1 or 1.12.1+cu116
torchaudio==0.12.1 or 0.12.1+cu116
torchvision==0.13.1 or 0.13.1+cu116
jupyter
opencv-python==4.6.0.66
streamlit==1.12.2
```

### Environment Setup

```
cd "directory\to\current\github\repo"
python make_environment.py
cd "Envir\Scripts"
activate
cd..
cd..
pip install -r requirements.txt
```
### Pytorch Installation
#### CPU
```
pip3 install torch torchvision torchaudio
```
#### GPU, CUDA
```
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu116
```
