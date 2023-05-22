# Google Colab CUDA Template
It is quite simple to get started with learning CUDA even if you do not own an NVidia GPU. Google collab offers users to use their GPU instances for free. Although it might not be ideal for high-performance computation, it is a great way to get started learning CUDA. This repository is a template for running CUDA C++ programs on Google Colab notebooks.

## Getting started with the template
To get started, the first step is to go to [Google Colab](https://colab.research.google.com/). After that, follow these steps:
* Download the 'cuda.ipynb' notebook file from this repository
* Go to File > Upload notebook
* Select the downloaded 'cuda.ipynb' notebook
* Once the notebook is open, go to Runtime > Change runtime type
* From the hardware accelerator dropdown, select GPU and click save.

You are now ready to run CUDA C++ or regular C++ code in this notebook.    

You might notice colab performs incorrect syntax highlighting for your C++ code, since it is usually checking for Python code. If this becomes a distraction, you can click on the settings button next to your profile on the top right, go to the Editor tab, and under 'Code diagnostics' select None.      