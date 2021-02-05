# Regularized FedAvg

### Requirements

TorchText requires nightly version

installed through pip

`pip install --pre torch torchtext torchvision -f https://download.pytorch.org/whl/nightly/cpu/torch_nightly.html`

other requirements could be found in requirements.txt

#### dataset

MNIST: 1x28x28, automatically downloaded from torchvision

CIFAR10: 3x32x32, resized as 3x28x28, automatically downloaded from torchvision

EMNIST: 1x28x28, automatically downloaded from torchvision

Sent140: manually download from `https://www.kaggle.com/kazanova/sentiment140/download`

### How to run

1. install the requirements

2. change the parameters in `config.yml`

3. python3 main.py