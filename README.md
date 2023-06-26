# CAT OR DOG

In the spirit of learning more about deep learning, I've trained a model on spotting either a cat or a dog.

It's wild to me that this would not have been possible just 5-10 years ago (or at least not without a whole team/large company's resources behind it).

I trained this while sitting in a bakery while drinking an afternoon's cup of coffee. Wild.

## INSTRUCTIONS

First, clone down this repo wherever you want it.

Next, set up [Anaconda](https://www.anaconda.com/) on your machine with the following steps:

1. Go to the [Anaconda downloads page](https://www.anaconda.com/download) and download the binary you need
2. Run the install process until it's finished
3. Open up a new terminal (or restart one you have open) and run `conda` (you should see valid output)
4. Check the current Anaconda environments by running `conda env list` (you should see only the `base` env)
5. Run the following commands in the base environment:
   - `conda install -c conda-forge notebook`
   - `conda install -c conda-forge nb_conda_kernels`
   - `conda install -c conda-forge jupyterlab`
   - `conda install -c conda-forge nb_conda_kernels`
   - `conda install pip`
6. Create a new environment by running `conda create --name <whatever name you want for the env>`
7. Activate the environment by running `conda activate <your environment name>` (you can get out of this later by running `conda deactivate <your environment name>`)
8. Install other deps specific to this environment by running `pip install duckduckgo_search fastcore fastdownload fastai`
9. Start up the jupyter notebook by running `jupyter notebook`

From here, you would have a browser window open with the running notebook. You should be able to successfully run the code cells and generate your own trained model if you want.
