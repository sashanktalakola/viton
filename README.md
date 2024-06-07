# Virtual Try-On


Dataset - [Marquis' VITON-HD](https://www.kaggle.com/datasets/marquis03/marquis-viton-hd)

## Experiments
1. **Baseline v0**
    * Simple U-Net architecture
    * Filters - `[16, 32, 64, 128]`
    * Image Size - `(384, 512)`
    * Augmentation - None
    * Epochs - `20`, Learning Rate - `1e-4`
    * Loss Function - MSE

2. **Baseline v0.2**
    * Simple U-Net architecture
    * Filters - `[16, 32, 64, 128]`
    * Image Size - `(384, 512)`
    * Augmentation - None
    * Epochs - `20`, Learning Rate - `1e-5`
    * Loss Function - MSE

3. **Baseline v0.3**
    * Simple U-Net architecture
    * Filters - `[64, 128, 256, 512]`
    * Image Size - `(288, 384)`
    * Augmentation - None
    * Epochs - `40`, Learning Rate - `1e-4`
    * Loss Function - MSE

> Simple U-Net Architectures tend to perform poorly