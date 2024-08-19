# spro-UFMG-2024
 
 Material for short course: stochastic programming and robust optimisation taught in the Department of Production Engineering at UFMG in August 2024.


## Using the notebooks

To run the notebook examples you will need [Julia](https://julialang.org/downloads/#install_julia) installed.

Once Julia is installed, run Julia to start your REPL and type

`]` to open the package manager

`activate .` to create an environment locally

`instantiate` to install the required packages to the environment.


## Opening the notebooks


### Using VSCode

To use the notebooks via on VSCode, you also need to install the Julia VSCode extension. 

### Using Jupyterlab

To use Julia via Jupyter notebooks, you need to install a package called `IJulia.jl`. The following commands will open a Jupyterlab session for you with a Julia kernel availabl.

Start by running Julia to start your REPL and type

`using IJulia` to load the package

`jupyterlab()` to start the Jupyterlab server.
 