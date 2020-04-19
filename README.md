# MNIST-to-SVHN and SVHN-to-MNIST

PyTorch Implementation of [CycleGAN](https://arxiv.org/pdf/1703.10593.pdf) .

![alt text](gif/cyclegan.png)


## Prerequites
* [Python 3.5](https://www.continuum.io/downloads)
* [PyTorch 0.1.12](http://pytorch.org/)


<br>

## Usage

#### Clone the repository

```bash
$ git clone https://github.com/yunjey/mnist-svhn-transfer.git
$ cd mnist-svhn-transfer/
```

#### Download the dataset
```bash
$ chmod +x download.sh
$ ./download.sh
```

#### Train the model

##### CycleGAN
```bash
$ python main.py --use_labels=False --use_reconst_loss=True
```

<br>

## Results

#### CycleGAN (should be re-uploaded)

From SVHN to MNIST            |  From MNIST to SVHN
:-------------------------:|:-------------------------:
![alt text](gif/cycle-s-m.gif)  |  ![alt text](gif/cycle-m-s.gif)
![alt text](gif/cycle-s-m.png)  |  ![alt text](gif/cycle-m-s.png)

