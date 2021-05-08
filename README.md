# setup

# **Windows python setup:**
1. Install Anaconda
2. Download math514_env6_noversion.yml from [math514_setup](https://github.com/gu-math514/setup)
3. Open anaconda terminal and cd to directory containing yml file

From anaconda terminal run:

conda env create -f math514_env6_noversion.yml

activate math514_env6

spyder

The spyder IDE should open and you should have access to the packages in the math514_env environment

# **OS-X python setup:**

almost same as windows -- use math514_env_osx.yml. Run commands from osx terminal.

conda env create -f math514_env_osx.yma

conda activate math514_env

spyder

# **Jupyter Notebook setup Windows**

1. Open anaconda prompt and activate latest math514 environment
2. If jupyter is not in current env then install: conda install jupyter
3. python -m ipykernel install --user --name math514_env6 --display-name "env6"
4. jupyter notebook

Now when notebook opens in the browser you should see 'env6' in the 'new' dropdown

**Jupyter Notebook Extensions**

[extensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)

1. From anaconda prompt, activate latest math514 env
2. conda install -c conda-forge jupyter_contrib_nbextensions
3. jupyter contrib nbextension install --user

Now, when you run 'jupyter notebook' you will see a 'Nbextensions' tab. 
Activate the following extensions (and any others you want to use):
- Hide input
- Table of Contents (2)
- Scratchpad
The 'Hide input' extension allows you to hide/display the contents of a cell using the up-arrow icon.
Tutorial notebooks have the 'solution' cells hidden initially.



