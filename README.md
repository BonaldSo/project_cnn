IMPLEMENTATION OF CNN AND APPLICATION OF CNN MODULES FROM PYTORCH

Data: images from 10 different classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)

      Train dataset split into train set and validation set (8:2)
      
My implementation: Convolution2D, Dropout, BatchNorm2D, cross entropy loss, SGD optimizer)

CNN structure: 3 full blocks(Convolution2D, batch normalization 2D, relu, maxpool), classifier, relu, dropout, fc layer

usage: the CNN takes the images data as input, and learn to identify those 10 different classes using 
50 epochs, 10 eval intervals, SGD optimizer.

result: we can see from the plot that both training and validation error are decreasing, so the CNN is able to learn
how to identify the images correctly. 
