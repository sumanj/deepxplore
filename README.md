# DeepXplore

## Prerequisit
### Python
The code should be run using python 2.7.12, Tensorflow 1.3.0, and Keras 2.0.8.

### Tensorflow
```bash
sudo pip install tensorflow
```
if you have gpu,
```bash
sudo pip install tensorflow-gpu
```

### Keras
```bash
sudo pip install keras
```

### Mimicus
Install from [here](https://github.com/srndic/mimicus)

## File structure
+ **MNIST** - MNIST dataset
+ **ImageNet** - ImageNet dataset
+ **Driving** - Udacity self-driving car dataset
+ **PDF** - Benign/malicious PDFs captured from VirusTotal/Contagio/Google provided by Mimicus
+ **Drebin** - Drebin Android malware dataset

# To run
```bash
python gen_diff.py
```
In every directory

# Note
The trained weights are provided in each directory (if required).
Drebin's weights are too large, downladed [here](https://drive.google.com/drive/folders/0B4otJeEcboCaQzFpYkJwb2h3WG8?usp=sharing) and put them in ./Drebin/
