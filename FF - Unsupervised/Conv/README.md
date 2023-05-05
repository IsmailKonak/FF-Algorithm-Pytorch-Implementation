# FF - Unsupervised - CNN

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

Layers used as input for the linear classifier = all

<br>

## Architecture:

Convolutional Layer (in_channels=1, out_channels=128, kernel_size=10, stride=6)

Convolutional Layer (in_channels=128, out_channels=220, kernel_size=3)

Convolutional Layer (in_channels=220, out_channels=512, kernel_size=2)

<br>

## Training info

**FF - Train time** = 3 min 0 s

**LC - Train time** = 8 min 56 s

**Train Loss** = 0.029 ( %2.9 )

**Train Accuracy** = 0.999 ( %99.9 )

**Test Loss**  =  0.0874 ( %8.7 )

**Test Accuracy**  =  0.994 ( %99.4 )

<br>

## Plots

---

![Untitled](FF%20-%20CNN%20323b756155c74ffea7db340dc9f6cc1e/Untitled.png)
