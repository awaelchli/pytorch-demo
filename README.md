# PyTorch Demo

This repository is built for the presentation given at the Future Talk 2019 event. 

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

This repository was prepared with PyTorch 1.1.0. 

#### [Jupyter Notebook][3] 

We will use Jupyter Notebook as an interactive code editor. First install it, then start:
~~~
conda install jupyter
jupyter notebook
~~~

This should open a new browser window. 

#### Everything Else

You will need a bunch of other packages, nothing fancy. Just run
```
pip install -r requirements.txt
```

You are ready to start coding!
Finally, when you are done working with your notebooks, deactivate the environment: 
~~~ 
conda deactivate
~~~

## Slides

The slides are available as an interactive Jupyter Notebook. If you want to use and adapt them yourself, you will need [RISE][4]:
~~~
conda install -c conda-forge rise
~~~
This is optional and not required to run and interact with the code. 

[1]: https://www.anaconda.com/distribution/ "Install Anaconda"
[2]: https://pytorch.org/ "Install PyTorch"
[3]: https://jupyter.org/install.html "Install Jupyter Notebook"
[4]: https://github.com/damianavila/RISE "RISE"

