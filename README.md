# MelGAN
An implementation of the MelGAN.  
Please refer to the [paper](https://arxiv.org/abs/1910.06711) for the original work.

## Code Origanization
```
|-- README.md             <- Top-level README.
|-- set_env.sh            <- Set PYTHONPATH and CUDA_VISIBLE_DEVICES.
|
|-- mel2wav
|   |-- dataset.py           <- data loader scripts
|   |-- modules.py           <- Model, layers and losses
|   |-- utils.py             <- Utilities to monitor, save, log, schedule etc.
|
|-- scripts
|   |-- train.py                    <- training / validation / etc scripts
|   |-- generate_from_folder.py
```

## Cite 
[1] Kundan Kumar, Rithesh Kumar, Thibault de Boissiere, Lucas Gestin, Wei Zhen Teoh, Jose Sotelo, Alexandre de Brebisson, Yoshua Bengio, Aaron Courville. "MelGAN: Generative Adversarial Networks for Conditional Waveform Synthesis" <https://arxiv.org/abs/1910.06711>
