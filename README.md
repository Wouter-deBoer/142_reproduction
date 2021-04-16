# 142_reproduction
Reproduction 'Hierarchical Image Classification using Entailment Cone Embeddings' for the TU Delft course Deep Learning.

1. Unpack .zip
2. Download ETHEC dataset v.0.1: https://www.research-collection.ethz.ch/handle/20.500.11850/365379
3. Install requirements_3.6.txt
4. Sample command:   
```
python learningembeddings/network/ethec_experiments.py --experiment_name exp_test   
--experiment_dir exp --image_dir ETHEC_dataset_v0.1/ETHEC_dataset/IMAGO_build_test_resized/   
--n_epochs 1 --model resnet50 --loss multi_level --set_mode train --json_path ./network/ETHEC 
```

Original repository found on: https://github.com/ankitdhall/learning_embeddings/blob/master/README.md   
This repository is a slightly modified version of the original.
