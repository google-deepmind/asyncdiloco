# Asynchronous Local-SGD Training for Language Modeling
This repository contains a Colab notebook that presents a minimal toy example replicating the observed optimization challenge in asynchronous Local-SGD.
The task is to perform classification on a mixture of mixtures of Gaussian data.

## Usage

We recommend executing the notebook using a PyTorch GPU kernel.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/google-deepmind/asyncdiloco/blob/master/AsyncLocalSGDToyExample.ipynb)

## Citing this work

If you use the colab in this package, please cite:

```bibtex
@misc{liu2024asynchronous,
      title={Asynchronous Local-SGD Training for Language Modeling},
      author={Bo Liu and Rachita Chhaparia and Arthur Douillard and Satyen Kale and Andrei A. Rusu and Jiajun Shen and Arthur Szlam and Marc'Aurelio Ranzato},
      year={2024},
      eprint={2401.09135},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

You can see the paper at https://arxiv.org/abs/2401.09135.

## License and disclaimer

Copyright 2023 DeepMind Technologies Limited

All software is licensed under the Apache License, Version 2.0 (Apache 2.0);
you may not use this file except in compliance with the Apache 2.0 license.
You may obtain a copy of the Apache 2.0 license at:
https://www.apache.org/licenses/LICENSE-2.0

All other materials are licensed under the Creative Commons Attribution 4.0
International License (CC-BY). You may obtain a copy of the CC-BY license at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless required by applicable law or agreed to in writing, all software and
materials distributed here under the Apache 2.0 or CC-BY licenses are
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the licenses for the specific language governing
permissions and limitations under those licenses.

This is not an official Google product.
