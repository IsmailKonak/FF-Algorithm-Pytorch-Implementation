# FF - CNN

## Dataset

**Dataset** = MNIST

**Train Sample Num** = 60 000

**Test Sample Num** = 10 000

<br>

## Parameters

**Batch Size** = 1024

**Optimizer** = Adam

**Learning Rate** **- FF** = 0.03

**Learning Rate - LC** = 0.05

**Epochs** = 50

**Threshold** = 2.0

Layers used as input for the linear classifier = 1,2,3,4 (0 is the input layer which is not included)


<br>

## Architecture:

Linear Layer : 784 neurons (input layer)

Linear Layer : 500 neurons

Linear Layer : 500 neurons

Linear Layer : 500 neurons

Linear Layer : 500 neurons

<br>

## Training info

**FF - Train time** = 0 min 47 s

**LC - Train time** = 6 min 35 s

**Train Loss** = 0.087 ( %8.7 )

**Test Loss**  =  0.0209 ( %20.9 )

<br>

## Device
**GPU**: GeForce RTX™ 3050 (Laptop)

## Plots

---

![loss_plot](https://github.com/IsmailKonak/FF-Algorithm-Pytorch-Implementation/blob/main/FF%20-%20Unsupervised/MLP/loss_plot.png)
