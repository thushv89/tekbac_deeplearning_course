## Using `conda` Environment for the TEKBAC Workshop

1. Download and install [Anaconda](https://www.anaconda.com/download/#windows)
2. Make sure conda is in the system `PATH` by trying `conda --version` in the command prompt
3. Create a conda virtual environment using `conda create -n tekbac.deeplearning python=3.5`
4. cd into the `<project directory>`
5. Install tensorflow by typing the following in the command prompt
6. If you **do not have a GPU** use: `conda install -n tekbac.deeplearning --yes --file requirements.txt`
7. If you **do have a GPU** use: `conda install -n tekbac.deeplearning --yes --file requirements_gpu.txt`
8. Activate the newly created environment with `activate tekbac.deeplearning`

Further reading on how to setup conda environments: [Here](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/)