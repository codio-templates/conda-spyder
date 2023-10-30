---

As mentioned before, Spyder uses Anaconda (also referred to as `conda`) to set up of the environment and manage additional packages. 


|||info
## Using Conda

Conda is already available in this stack.

If you need more information on how to install Conda, you can read more about it [here](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html).
|||
 
Spyder recommends to use a separate conda environment, so this stack has a environment called `base` (the default environment) and another one called `spyder-env` with the most common packages to run it:

- numpy
- scipy
- pandas
- matplotlib
- sympy
- cython

To list all the available environments you can use:

```bash
conda env list
```

If you need to activate the `spyder-env` environment or add more packages you can use the following command:

```bash
conda activate spyder-env
```

And to list all packages inside this environment, you can use:

```bash
conda list
```


|||info
## Additional packages

The easiest way to manage packages inside one environment is through `pip`.

Always remember to `activate` your desired environment first.
|||

## Running Spyder

To understand how Spyder is set up to auto-start, use your editor of choice to edit the `startup.sh` file. For example, `nano` is already available in this stack: 

```bash
nano /home/codio/startup.sh
```

This scripts enables the conda environment `spyder-env` and then runs the command `spyder` to open the application. If you use this stack, you don't need to make additional changes, we just recommend that you create your own stack using this one as template so that you have complete control over the underlying Operative System. 