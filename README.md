# EDDPG Implementation

This repository contains an implementation of EDDPG (Enhanced Deep Deterministic Policy Gradient) with the following configuration structure:

## 🛠 Configuration Files

### `Config_AC` - Network Parameters
- Contains neural network architecture specifications
- Defines actor-critic model configurations
- Includes learning rates and optimization parameters

### `Config_Env` - Experiment Parameters
- Environment-specific settings
- Training and evaluation configurations
- Resource allocation parameters

## 📚 Parameter Source

The experiment parameters are based on established research in following Reference:

### Key References:
1. **Miettinen, A. P., & Nurminen, J. K.** (2010)  
   *"Energy efficiency of mobile clients in cloud computing"*  
   📄 2nd USENIX Workshop on Hot Topics in Cloud Computing (HotCloud 10)

2. **Chen, M.-H., Liang, B., & Dong, M.** (2016)  
   *"Joint offloading decision and resource allocation for multi-user multi-task mobile cloud"*  
   📄 IEEE International Conference on Communications (ICC)  
   🔗 DOI: [10.1109/ICC.2016.7510695](https://doi.org/10.1109/ICC.2016.7510695)

## 🚀 Quick Start

```python
# Example usage
from eddpg import EDDPG
from config import Config_AC, Config_Env

agent = EDDPG(Config_AC, Config_Env)
