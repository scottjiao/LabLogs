

Cifar100 with grid washing method.
======================================

name | ResNet18 |  DenseNet121 |  MobileNetV2  |  ShuffleNetG2 |    MLP    
 :-: | :-: | :-: | :-: |  :-: | :-:
 0.1% |  X | X  |  X  |  X  |  X |
 1% | X  | X  |  X  |  X  |  X |
 10% | X  | X  |  X  | X   | X  |
100% |  X |  X |  X  | X   | X  |






Cifar100 with random sample method.
======================================

name | ResNet18 |  DenseNet121 |  MobileNetV2  |  ShuffleNetG2 |    MLP (with one hidden layer of 64 units)   
 :-: | :-: | :-: | :-: |  :-: | :-:
 0.1% |  20.53% | 23.90%  |  24.16%  |  task4  |  19.09% |
 1% | 38.95%  | task1  |  X  |  task5  |  28.40% |
 10% | 73.21%  | task2  |  X  |  task6  | 33.38%  |
100% |  92.83 |  task3 |  X  |  task9  | 36.03%  |
