# Setting up Anaconda Environment on Ubuntu 20.04 WSL2
  
[Link_to_Install_Miniconda_WSL2](https://towardsdatascience.com/configuring-jupyter-notebook-in-windows-subsystem-linux-wsl2-c757893e9d69 "Link_to_Install_Miniconda_WSL2")   

Why the miniconda setup is enough refer below link:

https://medium.com/dunder-data/anaconda-is-bloated-set-up-a-lean-robust-data-science-environment-with-miniconda-and-conda-forge-b48e1ac11646  

### Conda Generic Commands and Usage:  
- conda create -n minimal_ds (Create a new conda Virtual Python Env ) 
- conda config --env --add channels conda-forge (Adds to the Conda channles) 
- conda activate minimal_ds (Activate the newly created channels)
- conda config --show channels (Shows the available channels) 

### Command to run Jupyter Notebooks from WSL2:

- jupyter lab --no-browser (Opens jupyter lab)
- jupyter notebook --no-browser (Opens jupyter Notebook)
        - Copy paste the URL link output in the browser to see it in the GUI format. (Direct GUI isnt supported in linux env and we need to enable seperately.)
- We can work with the .ipynb Notebooks with  [Google_Collaboratory](https://colab.research.google.com/ "Google Collaboratory to make edits to .ipynb online") online as well. In case no personal laptop.