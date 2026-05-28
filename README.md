# CharGenAndRetopo
Multi-view full-body character 3D shape generation and auto retopology

## Environment
- **System**: Ubuntu 25.10
- **CUDA Toolkit**: CUDA 12.4
- **Python**: 3.12.13
- **PyTorch**: Make sure the PyTorch CUDA version matches your installed CUDA Toolkit. I used torch 2.6.0 for my current installed CUDA:
  ```bash
  pip install torch==2.6.0 torchvision==0.21.0 torchaudio==2.6.0 --index-url https://download.pytorch.org/whl/cu124
  ```
- **Torchsparse**:
  1. Install libsparsehash-dev:
  ```bash
  sudo apt-get install libsparsehash-dev
  ```
  2. Install Torchsparse:
  ```bash
  git clone https://github.com/mit-han-lab/torchsparse
  cd torchsparse && python setup.py install
  ```
