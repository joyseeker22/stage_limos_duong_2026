## Installation 
This project uses Python and an environment for Python. To set up the project, follow these steps: 
### Prerequisites
* Python 3.12
* A virtual environment that can be installed by using the requirements.txt
### Setting up
```bash
git clone https://github.com/joyseeker22/stage_limos_duong_2026.git
python -m venv venv1
.\venv1\Scripts\activate
pip install -r requirements.txt 
python3 src/problem/dataset_2fac.py
```
---
## Dataset
The dataset included in this repository is used for testing the code. In each dataset, a factory consists of multiple jobs scheduling scenarios with stochastic elements. 
Source: https://github.com/SamanNsr/Hybrid-Simheuristic-BiObj-Stoch-FJSSP.git

## Code 
The code generates a new dataset for 2 factories from the original one of only one factory. It maps out the compatibility of each job with specific machines across both factories and calculates the baseline distance between the facilities. The distance is randomly assigned between 1 and 10 km, assuming both factories operate within the same industrial hub. 
    
  
