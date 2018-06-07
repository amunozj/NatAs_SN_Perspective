# Repository of NatAs perspective:  "The Long-Term Sunspot Number Series: Challenges and Limitations"

## Important Limitations on using provided data

Data included in the _'input_data'_ folder are reduced versions of the published originals.  We request that you use them only to reproduce our figures, but not for your own research purposes.  Instead please go to the original sources:

*Sunspot Number Data*

* [SILSO World Data Center](http://www.sidc.be/silso/)
* Lockwood, M., Owens, M. J. & Barnard, L. Centennial variations in sunspot number, open solar flux, and streamer
belt width: 2. Comparison with the geomagnetic data. J. Geophys. Res. (Space Physics) 119, 5183–5192 (2014). DOI
10.1002/2014JA019972.
* Cliver, E. W. & Ling, A. G. The Discontinuity Circa 1885 in the Group Sunspot Number. Sol. Phys. 291, 2763–2784
(2016). DOI 10.1007/s11207-015-0841-6.
* Svalgaard, L. & Schatten, K. H. Reconstruction of the Sunspot Group Number: The Backbone Method. Sol. Phys. 291,
2653–2684 (2016). DOI 10.1007/s11207-015-0815-8.
* Chatzistergos, T., Usoskin, I. G., Kovaltsov, G. A., Krivova, N. A. & Solanki, S. K. New reconstruction of the sunspot
group numbers since 1739 using direct calibration and ”backbone” methods. Astron. & Astrophys. 602, A69 (2017). DOI
10.1051/0004-6361/201630045.
* Willamo, T., Usoskin, I. G. & Kovaltsov, G. A. Updated sunspot group number reconstruction for 1749-1996 using the
active day fraction method. Astron. & Astrophys. 601, A109 (2017). DOI 10.1051/0004-6361/201629839.

## Setting Up Your Modeling Environment ##

Requirements:

* Anaconda Python 3 installation.
* pyemd package.

### Anaconda Installation ###

You can find instructions for anaconda installation here:

* [Anaconda Windows installation instructions.](https://docs.anaconda.com/anaconda/install/windows)
* [Anaconda Mac-OS installation instructions.](https://docs.anaconda.com/anaconda/install/mac-os)
* [Anaconda Linux installation instructions.](https://docs.anaconda.com/anaconda/install/linux)

### Updating Conda Environment and Installing networkx ###

<a id='terminal'></a>
1. Start a terminal.  You can find instructions for opening terminals here:

  * [Open the Command Prompt program in Windows.](http://www.wikihow.com/Open-the-Command-Prompt-in-Windows)
  * [Start a temrminal in Mac-OS.](http://www.wikihow.com/Open-a-Terminal-Window-in-Mac)
  
2. Run the following commands.  They will update your python environment and install Pyemd.

> conda update --all  
> conda install astropy   
> pip install networkx 

### Clone or Download this Repository ###

Click on the _Clone or download_ button and clone it to a repository or download it as a zip file.

![GitHub Logo](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png)

If you want help cloning the repository and don't know how to do it let me know.  Otherwise, simply download the files and unpack them on a folder in your computer.


## Running the Jupyter Notebooks ##

1. Open a terminal ([see above](#terminal)).

2. Navigate to the folder where you unzipped the repository.  Here are some quick tutorials to use the terminal:
  * [Using the terminal in Windows](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands)
  * [Using the terminal in Mac-OS/Linux](https://computers.tutsplus.com/tutorials/navigating-the-terminal-a-gentle-introduction--mac-3855)
  
3. Run the following command:

> jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000

The _jupyter notebook_ command is normally sufficient, but the visualizations I'm including have a data rate limit to high for the defaults.  There is a way of fixing this permanently, but you need to mess up with configuration files.  More here:

* [Creating a configuration for jupyter](https://jupyter-notebook.readthedocs.io/en/latest/config.html)
* [Common Jupyter directories and file locations](https://jupyter.readthedocs.io/en/latest/projects/jupyter-directories.html)

4. Open the notebook.  Launching jupyter should open the dashboard in your folder.  Something that looks like this:

![Jupyter Dashboard](https://jupyter.readthedocs.io/en/latest/_images/tryjupyter_file.png)

Click on the notebook you want to open.

5. Run all cells or the cells you want.  For more information about running cells please see:

* [Running Jupyter Code](https://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Running%20Code.html)


## Jupyter Notebook Documentation: ##

More information about the Jupyter notebook can be found here:

* [Jupyter notebook documentation](https://jupyter-notebook.readthedocs.io/en/latest/index.html)
