# Quantum neural network(testing and verification)
 This is a repository for a Benchmark on Backdoor and Data Poisoning Attacks on quantum neural networks and hybrid quantum neural networks
### Quantum neural network
##### Clean network

| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|8-bit line classifier           | 48.0               |90.67         |

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
|4 class CIFAR10           | 99.2               | 68.9          |
##### Feature Collision
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|4 class CIFAR10           | 99.2               | 68.9          |
|2 class CIFAR10 ResNet           | 99.2               | 66.7          |
***
### Non-quantum neural network
##### Clean network
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 10.1               | 98.5          |
##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 99.8               | 97.5          |
