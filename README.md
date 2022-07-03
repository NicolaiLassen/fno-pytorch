# WORK IN PROGRESS

## Table of Contents

## Install

```bash
$ pip install no-pytorch
```

## Neural Operator - Pytorch

## Usage

```python
import torch
from no_pytorch import SpectralConv1d

spec_1d = SpectralConv1d(
            in_channels = 10,
            out_channels = 10,
            modes = 12
            )

x = torch.rand(1, 10, 64)

out = spec_1d(img) # (1, 10, 64)
```
## Resources



## Citations

```bibtex
@misc{https://doi.org/10.48550/arxiv.2205.13671,
  doi = {10.48550/ARXIV.2205.13671},
  url = {https://arxiv.org/abs/2205.13671},
  author = {Li, Zijie and Meidani, Kazem and Farimani, Amir Barati},
  keywords = {Machine Learning (cs.LG), Artificial Intelligence (cs.AI), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Transformer for Partial Differential Equations' Operator Learning},
  publisher = {arXiv},
  year = {2022},
  copyright = {Creative Commons Attribution 4.0 International}
}
```

```bibtex
@misc{https://doi.org/10.48550/arxiv.2105.14995,
  doi = {10.48550/ARXIV.2105.14995},
  url = {https://arxiv.org/abs/2105.14995},
  author = {Cao, Shuhao},
  keywords = {Machine Learning (cs.LG), Numerical Analysis (math.NA), FOS: Computer and information sciences, FOS: Computer and information sciences, FOS: Mathematics, FOS: Mathematics, 68T99, 65D15, 65M99, 65N99},
  title = {Choose a Transformer: Fourier or Galerkin},
  publisher = {arXiv},
  year = {2021},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```

```bibtex
@misc{li2020fourier,
      title={Fourier Neural Operator for Parametric Partial Differential Equations}, 
      author={Zongyi Li and Nikola Kovachki and Kamyar Azizzadenesheli and Burigede Liu and Kaushik Bhattacharya and Andrew Stuart and Anima Anandkumar},
      year={2020},
      eprint={2010.08895},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

*We may regard the present state of the universe as the effect of its past and the cause of its future. An intellect which at a certain moment would know all forces that set nature in motion, and all positions of all items of which nature is composed, if this intellect were also vast enough to submit these data to analysis, it would embrace in a single formula the movements of the greatest bodies of the universe and those of the tiniest atom; for such an intellect nothing would be uncertain and the future just like the past would be present before its eyes* — Marquis Pierre Simon de Laplace