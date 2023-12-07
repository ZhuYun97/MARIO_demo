## How to run?

`python unsupervised.py --config_path GOODCBAS/color/concept/MARIO.yaml --ad_aug`

`python unsupervised.py --config_path GOODWebKB/university/concept/MARIO.yaml --ad_aug`

Our codes are built up on [GOOD](https://github.com/divelab/GOOD).

## Requirements:

These installation commands are tailored for CUDA 12.1. For other versions, you can refer to their official websites for the appropriate instructions.

```
pip install torch_geometric

pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-2.1.0+cu121.html

pip install munch ruamel_yaml cilog gdown dive_into_graphs tensorboard rich
```
