# **setup**

# **Windows python setup:**
1. Install Anaconda
2. Download math514_env7_withversion.yml from [math514_setup](https://github.com/gu-math514/setup)
3. Open anaconda terminal and cd to directory containing yml file

From anaconda terminal run:

conda env create -f math514_env7_withversion.yml

activate math514_env7

spyder

The spyder IDE should open and you should have access to the packages in the math514_env environment

Note: 
Check your package versions using 'conda list'. If your pytorch version is before 1.8.1 try running:

conda upgrade -c pytorch pytorch

After the upgrade I have
- pytorch-1.8.1
- torchtext-0.9.1
- torchvision-0.9.1


# **OS-X python setup:**

almost same as windows -- use math514_env7_osx_withchannel.yml. Run commands from osx terminal.
This took a very long time on my vintage OSX mac-mini

conda env create -f math514_env7_osx_withchannel.yma

conda activate math514_env7

spyder

The OS-X versions of pytorch, torchtext, ... might be slightly different than on windows.

# **Jupyter Notebook setup**

1. Windows: Open anaconda prompt and activate latest math514 environment

   OS-X: Open OS-X terminal and activate latest math514 environment. OS-X does not have an anaconda terminal so all commands are entered in an os-x terminal.
3. If jupyter is not in current env then install: conda install jupyter
4. python -m ipykernel install --user --name math514_env7 --display-name "env7"
5. jupyter notebook

Now when notebook opens in the browser you should see 'env7' in the 'new' dropdown

# **Jupyter Notebook Extensions**

[extensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)

1. Windows: From anaconda prompt, activate latest math514 env

   OS-X: Open OS-X terminal and activate latest math514 environment
3. conda install -c conda-forge jupyter_contrib_nbextensions
4. jupyter contrib nbextension install --user

Now, when you run 'jupyter notebook' you will see a 'Nbextensions' tab. 
Go to the 'Nbextensions' tab and activate the following extensions (and any others you want to use):

- Table of Contents (2)
- Scratchpad
- Exercise

Tutorial notebooks have the 'solution' cells hidden initially.

**NOTE:** if extension checkboxes are disabled then uncheck the box: disable configuration for nbextensions without explicit compatibilit ...



