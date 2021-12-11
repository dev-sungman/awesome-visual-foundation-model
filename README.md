# Awesome-Visual-Foundation-Model

Collecting papers about visual foundation / general / univeral model.

## Why visual fondation model?
A visual model that was trained on a large amount of data recently performed admirably as a genralist.

**Any contributions, comments are welcome.**
<br></br>

# Zero-shot Image Retrieval (text->image)
| Conference / Journal             | Paper                                                        | Zero-shot result | 
| ---------------- | ------------------------------------------------------------ | --------------------- |
| arXiv:2001.07966     | [ImageBERT: Cross-modal Pre-training with Large-scale Weak-supervised Image-Text Data](https://arxiv.org/pdf/2001.07966.pdf) | COCO R@1: 32.3 |
| arXiv:2103.00020     | [CLIP: Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/pdf/2103.00020.pdf) | COCO R@1: 37.8|
| arXiv:2102.05918     | [ALIGN: Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision](https://arxiv.org/pdf/2102.05918.pdf) |COCO R@1: 45.6|
| arXiv:2111.07783     | [FLIP: FINE-GRAINED INTERACTIVE LANGUAGEIMAGE PRE-TRAINING](https://arxiv.org/pdf/2111.07783.pdf) | COCO R@1: 45.9 |
| arXiv:2111.11432     | [Florence: A New Foundation Model for Computer Vision](https://arxiv.org/pdf/2111.11432.pdf) | COCO R@1: 47.2 |
<br></br>

# Zero-shot Image Classification
### Dataset: ImageNet
| Conference / Journal             | Paper                                                        | Zero-shot result (Top-1 Acc.) | 
| ---------------- | ------------------------------------------------------------ | --------------------- |
| arXiv:2103.00020     | [CLIP: Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/pdf/2103.00020.pdf) | 10%: 72.6 (ResNet-50), 100%: 73.3 (ResNet-50), 80.2 (ViT-B/16) |
| arXiv:2102.05918     | [ALIGN: Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision](https://arxiv.org/pdf/2102.05918.pdf) |100%: 76.4 (EfficientNet-L2)|
| arXiv:2111.07783     | [FLIP: FINE-GRAINED INTERACTIVE LANGUAGEIMAGE PRE-TRAINING](https://arxiv.org/pdf/2111.07783.pdf) | 100%: 78.3 (ViT-L/14) |
| arXiv:2111.11432     | [Florence: A New Foundation Model for Computer Vision](https://arxiv.org/pdf/2111.11432.pdf) | 100%: 83.7 (CoSwin-H@384) |
<br></br>

# Zero-shot Image Detection
| Conference / Journal             | Paper                                                        | Zero-shot result (mAP) | 
| ---------------- | ------------------------------------------------------------ | --------------------- |
| arXiv:2111.11432     | [Florence: A New Foundation Model for Computer Vision](https://arxiv.org/pdf/2111.11432.pdf) | BCCD: 15.3, Oxford Pets: 68.9 |
<br></br>

# Few-shot / Percentage-shot Image Classification
## Finetune evaluation
| Conference / Journal             | Paper                                                        | Zero-shot result (Top-1 Acc.) | 
| ---------------- | ------------------------------------------------------------ | --------------------- |
| arXiv:2103.00020     | [CLIP: Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/pdf/2103.00020.pdf) | ImageNet 100%: 73.3 (ResNet-50), 80.2 (ViT-B/16) |
| arXiv:2111.08687     | [INTERN: A New Learning Paradigm Towards General Vision](https://arxiv.org/pdf/2111.08687.pdf) | ImageNet 100%: 88.4 (MN-B15)|