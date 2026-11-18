# Applika models

AI models downloaded on first use by [Applika](https://inferam.eu) (Infera M). Applika fetches them from the
Release `v1` of this repository and checks the md5 before use.

| File | Used for | Size | md5 |
|---|---|---|---|
| `realesrgan-x4plus-anime.onnx` | Upscale – AI illustration (logos, lettering, drawings) | 17.9 MB | `42102eb8359bd7821fe040c6c2a4f7ea` |
| `realesr-general-x4v3.onnx` | Upscale – AI photo | 4.9 MB | `81473dc70763e5bc932ced5569c1db00` |

Both are [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) models by Xintao Wang et al., converted from the
original PyTorch weights to ONNX without retraining (output matches PyTorch within 1e-5). Licensed under the
BSD 3-Clause License – see `LICENSE`.
