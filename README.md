# PyTorch Demo

Learn PyTorch by example. This repository is built for the presentation given at the Future Talk 2019 event. 

## Prerequisites 

For ease of use, I recommend you install the following software packages in advance.

#### [Anaconda 3][1]

Download and install the 3.x version of Anaconda. It comes with Python 3. After installation, make sure that the command 'conda' is a recognized command. If not check that ```INSTALL_DIR/anaconda3/bin``` is included in your path variable. 

Create a new environment: 

~~~
conda create -n pytorch-demo python=3.7
~~~

Activate the environment: 
~~~
conda activate pytorch-demo
~~~

#### [PyTorch][2] 

If you have a system with an NVIDIA graphics card that supports CUDA, choose the installation for GPU, otherwise install the CPU-only version. 
- GPU: ``` conda install pytorch torchvision cudatoolkit=10.0 -c pytorch ``` 
- CPU: ``` conda install pytorch-cpu torchvision-cpu -c pytorch ``` 
This presentation is prepared for PyTorch 1.1.0. 

#### [Jupyter Notebook][3] 

We will use Jupyter Notebook as an interactive code editor. First install it, then start it like so:
~~~
conda install jupyter
jupyter notebook
~~~


Finally, if you are done working with the code, deactivate the environment: 
~~~ 
conda deactivate
~~~

## Slides

The slides are available as an interactive Jupyter Notebook. 


[1]: https://www.anaconda.com/distribution/ "Install Anaconda"
[2]: https://pytorch.org/ "Install PyTorch"
[3]: https://jupyter.org/install.html "Install Jupyter Notebook"

