# ANN-HandrwitingRecognition

## Specification
The goal is to create a neural network capable of recognizing handwritten digits. Training data consists of digits written in different people’s handwriting. Modular code will be written that implements the concept of perceptrons and their connections in a network, feeds forward the inputs, calculates the output function, calculates error, backpropagates error, and adjusts weights appropriately. Will train the neural network using the attached training data, then validating with validation set.

## Dataset
The dataset consists of image bitmaps. Each bitmap originally consisted of 32x32 = 1024 black-and-white pixels (0|1). The images have been compressed using 4x4 blocks, each holding a value 0..16 that represents the number of bits turned on in that 4x4 block. Therefore, the 32x32 = 1024 bit values are transformed into 8x8 = 64 integer values representing pixel intensities.
Each line in the file represents one image and contains 64 comma-separated integer values (0..16) and a target value (0..9).

- Training set instances: 3823
- Test set instances: 1797
- Integer data: 64 values (0..16) representing an 8x8 bitmap image of a number
- Targets: the digits 0..9

*Data provided by from Dr. Gregory Wolffe*
