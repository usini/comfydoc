
## Installation ComfyUI-3D-Pack
https://github.com/MrForExample/ComfyUI-3D-Pack

# CUDA 12.4
![](https://private-user-images.githubusercontent.com/2841495/391099205-33c5fe0b-1513-4ca0-b513-b34e8defef8c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzI4ODcxMDUsIm5iZiI6MTczMjg4NjgwNSwicGF0aCI6Ii8yODQxNDk1LzM5MTA5OTIwNS0zM2M1ZmUwYi0xNTEzLTRjYTAtYjUxMy1iMzRlOGRlZmVmOGMucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MTEyOSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDExMjlUMTMyNjQ1WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9ZmM2YmUzNWJkNzMxODRmN2E5N2YyOGEyZTA0NjY5YjkxYWIxYmY3NTJhYjEzMTk2YTU5OGUzMjE4YzdkMDJhMyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.SNemUK8bm3XU26KaMrAyLGxvyTrTh7nROH_FULTzTqs)
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

Attention : Try fix a tendance à annuler les modifications!!

## Utiliser le python Comfyui
```
cd ComfyUI_windows_portable\python_embeded
```

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
# Méchant NINJA!
https://github.com/ninja-build/ninja/releases
RuntimeError: Ninja is required to load C++ extensions

Copier dans un dossier accessible à PATH
```
ninja --version
```

# TORCH_CUDA_ARCH_LIST is not set
https://developer.nvidia.com/cuda-gpus
Geforce RTX 2070	- 7.5
GeForce RTX 4060	- 8.9

# Plotly
https://plotly.com/python/
Juste un warning mais bon...
```
python -m pip install plotly
```
