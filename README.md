Official implementation of [Lung Nodule Classification using Deep Local-Global Networks](https://arxiv.org/abs/1904.10126) using PyTorch 
## Install pre-requested libraries
- PyTorch 1.0
- Sklearn
## Steps to reproduce the results
- download the pre-processd [dataset](https://drive.google.com/file/d/19JMK_IeBFlEQAEt_nrWsJcHrdyHcZMhm/view?usp=sharing) 
- extract the dataset to a folder
- run `python experiments.py <experiment name> <path to the dataset>` (example: python experiments.py LocalGlobal lidc_img/)
## Notes
- LocalGlobal as the experiment name has the highest accuracy
- in experiments.py, the batch size of the expLocalGlobal function was reduced due to GPU limitations. Increase it back to 256 when we have access again to more a powerful GPU

