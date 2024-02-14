# Quantum neural network(testing and verification)
 This is a repository for a Benchmark on Backdoor and Data Poisoning Attacks on quantum neural networks and hybrid quantum neural networks
### Quantum neural network
##### Clean network

| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|8-bit line classifier           | 48.0               | 77.33         |

##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|8-bit line classifier           | 94.0               | 79.33          |
***
### Hybrid quantum neural network
##### Clean network
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 10.3               | 90.0          |
|4 class CIFAR10           | 22.9               | 72.2          |
##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 99.1               | 86.0          |
|4 class CIFAR10           | 99.2               | 67.8          |
***
### Non-quantum neural network
##### Clean network
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 10.1               | 94.5          |
##### BadNets 
| Dataset                       | Attack success rate (%)      | Clean test data (%)|
| ------------------            |-------------------:|-------------:|
|10 class MNIST           | 99.8               | 97.5          |
