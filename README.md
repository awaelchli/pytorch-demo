# PyTorch Demo

Learn PyTorch by example. This repository is built for the presentation given at the Future Talk 2019 event. 

## Prerequisites 

For ease of use, I recommend you install the following software packages in advance.

1. [Anaconda 3][1]: Download and install the 3.x version of Anaconda. It comes with Python 3. After installation, make sure that the command 'conda' is a recognized command. If not check that ```INSTALL_DIR/anaconda3/bin``` is included in your path variable. 
2. Create a new environment: ```conda create -n pytorch-demo python=3.7```
3. Activate the environment: ```conda activate pytorch-demo```
4. Install [PyTorch][2]: If you have a system with a NVIDIA graphics card, choose the installation for GPU, otherwise install the CPU-only version. 
   * GPU: ``` conda install pytorch torchvision cudatoolkit=10.0 -c pytorch ``` 
   * CPU: ``` conda install pytorch-cpu torchvision-cpu -c pytorch ``` 
5. Deactivate the environment: ``` conda deactivate ```


[1]: https://www.anaconda.com/distribution/ "Install Anaconda"
[2]: https://pytorch.org/ "Install PyTorch"

