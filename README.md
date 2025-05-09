# ETA Prediction & Routing

This repo demonstrates end-to-end ETA prediction (PyTorch 2) and route optimization (scikit-opt GA).

## Requirements

- Python 3.10+  
- pip  

## Setup

```bash
# 1. Clone / place these files in a folder, then:
python -m venv .venv
source .venv/bin/activate

# 2. Install dependencies:
pip install -r requirements.txt

# 3. Generate synthetic data & train model:
python data_generator.py
python train.py

# 4. Try route optimization alone:
python routing.py

# 5. Try prediction alone:
python predict.py

# 6. Full demo (optimize + predict):
python main.py
