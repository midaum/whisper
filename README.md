# Whisper

Vor der Nutzung von Whisper müssen ein NVIDIA CUDA-Treiber und Python installiert werden:
- [NVIDIA CUDA Downloads](https://developer.nvidia.com/cuda-downloads)
- [Python Downloads](https://www.python.org/)

Anschließend muss ein Jupyter Notebook eingerichtet werden, um die folgenden Codezeilen auszuführen:

```sh
!pip install git+https://github.com/openai/whisper.git
!pip install blobfile
!pip install torch
!pip install imageio[ffmpeg]
```

Anschließend kann die Transkription erfolgen.