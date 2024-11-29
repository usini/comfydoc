
## Installation ComfyUI-3D-Pack
https://github.com/MrForExample/ComfyUI-3D-Pack

# CUDA 12.4

## Prérequis
* Visual Studio Community 2022
* Compilation C++

## Installation

https://developer.nvidia.com/cuda-12-4-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local

## Modifier Variable d'environnement

* Variables systèmes
* Path

````
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.4\include
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.4\extras\CUPTI\lib64
C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.4\bin
````

# Python

## Activer python Comfyui
cd ComfyUI_windows_portable\python_embeded\Scripts
activate


# TORCH 2.5.1cu124
https://pytorch.org/get-started/locally/

```
python -m pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
```

```
import torch
torch.__version__
```

# Paquets manquants

## KIUI
https://pypi.org/project/kiui/
```
python -m pip install kiui
```

## onnxruntime (nécessaire pour rembg)
https://onnxruntime.ai/docs/install/
```
python -m pip install onnxruntime-gpu
```

## rembg
https://github.com/danielgatis/rembg

```
python -m pip install rembg[gpu]
```
