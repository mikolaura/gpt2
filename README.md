## Prerequisites
- Python 3.11.9

## 1. Install dependencies
```bash
# install PyTorch
pip install torch torchvision torchaudio
# or you can install with gpu
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

# install other dependencies
pip install numpy tiktoken tokenizers transformers dataclasses
```

## 2. Run the script
```bash
python demo_gpt2.py
```