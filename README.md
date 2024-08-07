

### 🧬 Code
https://github.com/black-forest-labs/flux



### docker
docker build  -t flux .

docker run  --gpus all -v ./models:/content/ComfyUI/models/ -p 7860:7860 flux

### model
```
models/
├── clip
│   ├── clip_l.safetensors
│   └── t5xxl_fp8_e4m3fn.safetensors
├── unet
│   ├── flux1-dev-fp8.safetensors
│   └── flux1-schnell-fp8_e4m3fn_unet.safetensors
└── vae
    └── ae.sft
```

https://huggingface.co/camenduru/FLUX.1-dev/tree/main
