## Prerequisites
- Python 3.11.9

## 1. Install dependencies
```bash
pip install torch 
# or you can install with gpu
pip3 install torch --index-url https://download.pytorch.org/whl/cu118
pip install numpy tiktoken tokenizers transformers dataclasses
```

## 2. Run the script
```bash
python train_gpt2.py
```