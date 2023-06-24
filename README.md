# [Lossless Segmentation of Brain Tumors from MRI Images using 3D U-Net - paper](https://ieeexplore.ieee.org/document/10089263/keywords#keywords)

##### System's Minimum Requirements:
   1. 8 GB RAM
   2. Core i5 processor
   3. Mid-level GPU
   4. 200 GB free space in the `c:` drive (**SSD**)
   5. Latest version of `Anaconda` has to be installed

[Download the Brats2020 Dataset](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data)

Then go to the `MICCAI_BraTS2020_TrainingData` folder and the `BraTS20_Training_355/` has a weird name file!
Therefore, rename it with `BraTS20_Training_355_seg.nii`


###### Steps to install the environment:

   1. Clone this Repository via `git clone https://github.com/SowatRafi/Lossless-Segmentation-of-Brain-Tumors-from-MRI-Images-using-3D-U-Net.git` into your git terminal.
   2. Open your *cmd / powershell / terminal* and go to the **Lossless Segmentation of Brain Tumors from MRI Images using 3D U-Net** folder.
    Example: You have cloned that in the Downloads folder.
    
    cd Downloads/Lossless-Segmentation-of-Brain-Tumors-from-MRI-Images-using-3D-U-Net/
    
   3. Activate your conda `conda activate` (**base**)
   4. Now type `conda create --name 3D-UNet --file Conda_Requirements-Windows.txt` or `conda create --name 3D-UNet --file Conda_Requirements-macOS.txt`
   5. Now type `conda activate 3D-UNet` to activate the environment and `conda deactivate` to deactivate the setting.

**_Now you are eligible to play with this thing_** 😎
