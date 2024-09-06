# Installation Steps

1. Install Chrome and download the corresponding version of Chromedriver for your operating system.

[Link to chromedriver download](https://googlechromelabs.github.io/chrome-for-testing/#stable)

2. Create a venv and install the dependencies with `pip install -r requirements.txt`

3. All methods of Helium are documented here:
[GitHub Link](https://github.com/mherrmann/helium/blob/0667ddb9be531367a0d707ad8f5fcfb75c528521/helium/__init__.py#L281)



## QWEN-VL Installation 

1. Install first dependencies
```
pip install optimum

pip install auto-gptq
```

2. Install from source
```
pip install git+https://github.com/huggingface/transformers
```

3. Install torch
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu122
```

