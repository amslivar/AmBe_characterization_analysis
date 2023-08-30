Python code to plot, re-bin and save the simulated spectrum of AmBe without outer tungsten capsule in remote position.

python version: Python 3.10.10

jupyter version:
    
    IPython          : 8.14.0
    
    ipykernel        : 6.24.0
    
    ipywidgets       : not installed
    
    jupyter_client   : 8.3.0
    
    jupyter_core     : 5.3.1
    
    jupyter_server   : 2.7.0
    
    jupyterlab       : 4.0.3
    
    nbclient         : 0.8.0
    
    nbconvert        : 7.6.0
    
    nbformat         : 5.9.1
    
    notebook         : 6.5.4
    
    qtconsole        : not installed
    
    traitlets        : 5.9.0
    
    matplotlib version: 3.7.2
    
    numpy version: 1.25.1
    
    pandas version 2.0.3
    
    scipy version 1.11.1
    
    iminuit version 2.22.0

Author: Mariia Fedkevych, mariia.fedkevych@gmail.com

1. Download and open Analysis_GeSim_AmBe_remote_noW.ipynb as a jupyter notebook. Give a correct path to the output simulation .root file produced by the code in AmBe_GeSim_full_spectrum_remote_noW, and run the code.

2. It will produce a .npz archive with the simulated spectrum data re-binned accordingly to the measured spectrum for comparison made with the code in AmBe_characterization_analysis
/AmBe-2_noW_remote_with_attenuator/.
