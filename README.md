# AppliedAI_Course


- In case of rendering issue and unable to open the .ipynb notebooks we can open it the https://nbviewer.org/
- Open the URL and enter the github link to .ipynb (make sure the github link is publicly accessible) 

# Setting up Anaconda Environment on Ubuntu 20.04 WSL2 /Linux based environments.
  
[Link_to_Install_Miniconda_WSL2](https://towardsdatascience.com/configuring-jupyter-notebook-in-windows-subsystem-linux-wsl2-c757893e9d69 "Link_to_Install_Miniconda_WSL2")   

Install all the required list of libraries that needs to be used. In the below details just install the libraries as from the above link we are already installing the minconda on WSL2.

For step by step instruction refer to the **installation.ipynb** . You can also refer this video (https://www.youtube.com/watch?v=hbUJ6nd-9lA)


# System Setup

## before we dive into ML lets setup our systems so that we can work with all our assignments, without facing problems


### NOTE # Follow these steps for windows. For Linux/ WSL2 we dont requrie to do this setup. follow(Setting up Anaconda Environment on Ubuntu 20.04 WSL2) above
		# as a first step lets install anaconda, you can choose the link that are mentioned below
		choose the link which suits for your config
		# as i am using windows 64bit system i will be downloading it with this link
		https://repo.continuum.io/archive/Anaconda3-5.2.0-Windows-x86_64.exe 

		# you can see its downloading.
		# you can see its downloaded
		#lets install it by clicking it
		# make sure in that installation path there should not be any spaces 
		# its better you install it like this 
		# make sure that you click on that "add path" if you missed this part you might see some glitches while installing packages

		#installation is complete
		# lets just verify it
		# its your call to install vs code if you want you can skip it
		# its working fine

		1. installing anaconda 
			Windown 64 bit: https://repo.continuum.io/archive/Anaconda3-5.2.0-Windows-x86_64.exe 
			Windown 32 bit: https://repo.continuum.io/archive/Anaconda3-5.2.0-Windows-x86.exe 
			Mac : https://repo.continuum.io/archive/Anaconda3-5.2.0-MacOSX-x86_64.sh 
			Linux 64 bit: https://repo.continuum.io/archive/Anaconda3-5.2.0-Linux-x86_64.sh 
			Linux 32 bit: https://repo.continuum.io/archive/Anaconda3-5.2.0-Linux-x86.sh 
			Check the previous Archives of Anaconda: https://repo.continuum.io/archive/

```

# we will be installing all these packages and verifying

- Package to be install
1. plotly --- done
2. gensim -- done
3. graphviz -- this is used to plot decision tree, dask dataframe tree, DL models etc
#  i have stopped kernle lets start jupyter notebook  --- done

4. distance: note that this package is not part of the conda so we will be installing it with pip -- done
5. fuzzy wazzy -- done
6. imblearn -- done
7. networkx -- done
8. spacy - done
9. foulim -- done
10. tensorflow (only cpu) -- very usefull for DL -- done
11. keras -- done
12. prettytable - done
13. tqdm - done
14. xgboost
16. gpxpy
18. nltk.stopwords
19. skmultilearn
20. surprise
21. stellargraph
22. tensorboard

```

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

## Google Collab Usage:

