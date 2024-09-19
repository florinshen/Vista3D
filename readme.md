
## Vista3D: Unravel the 3D Darkside of a Single Image
<img width="800" alt="vista3d-teaser" src="https://github.com/user-attachments/assets/5ee6f213-6cc2-4add-abd2-ff2c727a0116">


### [Arxiv](https://arxiv.org) | [Demo]()


> We embark on the age-old quest: unveiling the hidden dimensions of objects
from mere glimpses of their visible parts. To address
this, we present Vista3D, a framework that realizes swift and consistent
3D generation within a mere 5 minutes. At the heart of Vista3D
lies a two-phase approach: the coarse phase and the fine phase. In the
coarse phase, we rapidly generate initial geometry with Gaussian Splatting
from a single image. In the fine phase, we extract a Signed Distance Function (SDF) directly from learned Gaussian Splatting, optimizing
it with a differentiable isosurface representation. Furthermore, it
elevates the quality of generation by using a disentangled representation
with two independent implicit functions to capture both visible and
obscured aspects of objects. Additionally, it harmonizes gradients from
2D diffusion prior with 3D-aware diffusion priors by angular diffusion
prior composition. 





### Citation

```bibtex
@article{Vista3D,
  title={Vista3D: Unravel the 3D Darkside of a Single Image},
  author={Shen, Qiuhong and Yang, Xingyi, Michael Bi, Mi and Wang, Xinchao},
  journal={European Conference of Computer Vision},
  year={2024}
}
```

