# ARBEx: Attentive Feature Extraction with Reliability Balancing for Robust Facial Expression Learning
### Azmine Toushik Wasi*, Karlo Serbetar*, Raima Islam*, Taki Hasan Rafi*, and Dong-Kyu Chae

---
### State-of-the-Art results in multiple datasets as per [Papers with Code](https://paperswithcode.com/paper/arbex-attentive-feature-extraction-with)
- RAF-DB : [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/arbex-attentive-feature-extraction-with/facial-expression-recognition-on-raf-db)](https://paperswithcode.com/sota/facial-expression-recognition-on-raf-db?p=arbex-attentive-feature-extraction-with)
- FER+ : [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/arbex-attentive-feature-extraction-with/facial-expression-recognition-on-fer-1)](https://paperswithcode.com/sota/facial-expression-recognition-on-fer-1?p=arbex-attentive-feature-extraction-with)
- JAFFE: [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/arbex-attentive-feature-extraction-with/facial-expression-recognition-on-jaffe)](https://paperswithcode.com/sota/facial-expression-recognition-on-jaffe?p=arbex-attentive-feature-extraction-with)
---

## Architecture
 Pipeline of ARBEx.
<p align="center">
  <img src="Images/Figure.PNG" width="700"/>
</p>

## Setup and run
Put pretrained `ir50.pth` and `mobilefacenet.pth` into `arbex/models/pretrained`.
By default, data is assumed to be in `../../_DATA`.
To change the default paths, change `DIR_IMG`, `DIR_ANN_TRAIN`, `DIR_ANN_DEV` in `arbex/config.py`
To install the dependencies run:
```
pip install -r requirements.txt
```
To run the training script:
```
python train.py
```

## References
[POSTER_V2](https://github.com/talented-q/poster_v2) \
[ViT](https://github.com/huggingface/pytorch-image-models)
