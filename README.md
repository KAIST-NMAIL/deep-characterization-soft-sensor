# deep-characterization-soft-sensor

This is code for calibrating microfluidic soft sensors, used in the following paper: 
* S Han, T Kim, D Kim, Y Park, S Jo, Use of Deep Learning for Characterization of Microfluidic Soft Sensors, IEEE RA-L, 3(2): 873-880, 2018 [Link](https://ieeexplore.ieee.org/document/8255560/)

We implemented this code, under the following packages:
* Python 3.5.4
* Tensorflow 
* Numpy

## How to train
```bash
python main.py --epoch 100
```

## How to test
After training, it saves checkpoint in the ./ckpt folder.
You can retrieve checkpoints by setting --test flag 'True'.
```bash
python main.py --epoch 100 --test True
```
