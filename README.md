# Quantum neural network(testing and verification)
 ![Python 3.10.6](https://img.shields.io/badge/python-3.10.6-DodgerBlue.svg?style=plastic)
 ![Pytorch 2.1.0](https://img.shields.io/badge/pytorch-2.1.0-DodgerBlue.svg?style=plastic)
 ![torchvision 0.16.0](https://img.shields.io/badge/torchvision-0.16.0-DodgerBlue.svg?style=plastic)  
 This is a repository for a Benchmark on Backdoor and Data Poisoning Attacks on quantum neural networks and hybrid quantum neural networks
 The test has been made on 6 types of attacking methods, including pure data poisoning attacks, backdoored data poisoning attacks and non data
 poisoned backdoor attacks. CIFAR10 is reduced to 4 classes to have a better training time as running quantum simulations will require large time.  
 To run the codes qiskit and qiskit-machine-learning is needed by
 ```
 pip install qiskit
 pip install qiskit_machine_learning
```
 To run the Feature Collison code ART is needed by
 `pip install adversarial-robustness-toolbox`
 
 To run LIRA and WaNet a modified version of [BackdoorBox](https://www.researchgate.net/publication/359439455_BackdoorBox_A_Python_Toolbox_for_Backdoor_Learning) is required on [mod-BackdoorBox](https://github.com/agrzheng/BackdoorBox), download  it and put it in the same folder of this repository. The github page for the original BackdoorBox will be(https://github.com/THUYimingLi/BackdoorBox)

 To run the general benchmark on the exisiting models just run the notebooks named with benchmark.  
**Note**: Hybrid networks may require a very long time to compute.  
The results will be shown below.
### Quantum neural network
##### Clean network

| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|8-bit line classifier           | x               |90.67         |

##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|8-bit line classifier           | 88.0               | 83.33          |
***
### Hybrid quantum neural network
##### Clean network
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | x               | 90.0          |
|4 class CIFAR10           | x               | 72.2          |
|2 class CIFAR10 ResNet           | x               | 81.5          |
##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 99.1               | 86.0          |
|4 class CIFAR10           | 99.2               | 68.2          |
##### Feature Collision
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 99.2               | 68.9          |
|2 class CIFAR10 ResNet           | 99.2               | 66.7          |
##### BitTrojan
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 61               | 66.0          |
##### LIRA
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 83.5               | 38.25          |
##### Sleeper Agents
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 14.7               | 73.7          |
***
### Non-quantum neural network
##### Clean network
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | x               | 98.5          |
|4 class CIFAR10           | x               | 71.0          |
|2 class CIFAR10 ResNet           | x               |94.9           |
##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 99.8               | 97.5          |
|4 class CIFAR10           | 97.0               | 70.5          |
##### Feature Collision
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 10               | 67.8          |
|2 class CIFAR10 ResNet           | 10               | 70.7          |
##### BitTrojan
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 93.5               | 65.0          |
##### LIRA
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 80.25               | 41.5          |
##### Sleeper Agents
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 27.2               | 75.8         |
