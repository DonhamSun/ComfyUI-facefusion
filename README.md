# FaceFuison extension for ComfyUI

[FaceFusion](https://github.com/facefusion/facefusion) is a very nice face swapper and enhancer.

#### 使用说明

1. 下载模型文件放置到对应位置，ComfyUI-facefusion是在custom_nodes目录下，

```
|-- ComfyUI-facefusion
  |-- .assets
    |-- models
      |-- 2dfan4.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/2dfan4.hash
      |-- 2dfan4.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/2dfan4.onnx
      |-- dfl_xseg.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/dfl_xseg.hash
      |-- dfl_xseg.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/dfl_xseg.onnx
      |-- gfpgan_1.4.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/gfpgan_1.4.hash
      |-- gfpgan_1.4.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/gfpgan_1.4.onnx
      |-- kim_vocal_2.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/kim_vocal_2.hash
      |-- kim_vocal_2.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/kim_vocal_2.onnx
      |-- retinaface_10g.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/retinaface_10g.hash
      |-- retinaface_10g.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/retinaface_10g.onnx
      |-- yoloface_8n.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/yoloface_8n.hash
      |-- yoloface_8n.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/yoloface_8n.onnx
      |-- arcface_w600k_r50.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/arcface_w600k_r50.hash
      |-- arcface_w600k_r50.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/arcface_w600k_r50.onnx
      |-- fairface.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/fairface.hash
      |-- fairface.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/fairface.onnx
      |-- inswapper_128_fp16.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/inswapper_128_fp16.hash
      |-- inswapper_128_fp16.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/inswapper_128_fp16.onnx
      |-- open_nsfw.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/open_nsfw.hash
      |-- open_nsfw.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/open_nsfw.onnx
      |-- scrfd_2.5g.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/scrfd_2.5g.hash
      |-- scrfd_2.5g.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/scrfd_2.5g.onnx
      |-- bisenet_resnet_34.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/bisenet_resnet_34.hash
      |-- bisenet_resnet_34.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/bisenet_resnet_34.onnx
      |-- fan_68_5.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/fan_68_5.hash
      |-- fan68_5.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/fan_68_5.onnx
      |-- inswapper_128.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/inswapper_128.hash
      |-- inswapper_128.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/inswapper_128.onnx
      |-- peppa_wutz.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/peppa_wutz.hash
      |-- peppa_wutz.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/peppa_wutz.onnx
      |-- span_kendata_x4.hash  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/span_kendata_x4.hash
      |-- span_kendata_x4.onnx  #https://github.com/facefusion/facefusion-assets/releases/download/models-3.0.0/span_kendata_x4.onnx
  
```

2. pip install -r requirements.txt
