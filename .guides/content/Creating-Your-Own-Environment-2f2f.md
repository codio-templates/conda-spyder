---

To create your own Conda environment, you can refer to the instructions available on [their website](https://docs.spyder-ide.org/current/installation.html#installing-with-conda). The basic command you need for the standalone installation is:

```bash
conda create -c conda-forge -n spyder-env spyder
```

Alternatively, you can also use the `export` command available in conda to export this environment:

```bash
conda env export > environment.yml
```

And then use the file `environment.yml` inside another stack that already has conda installed:

```bash
conda env create -f environment.yml
```

## More Help?

If you need more help setting up your environment, please refer to the following websites:

#### Installing Conda: 
[https://conda.io/projects/conda/en/latest/user-guide/install/linux.html](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html)

#### Managing Conda Environments: 
[https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

#### Installing Spyder:
[https://docs.spyder-ide.org/current/installation.html#installing-with-conda](https://docs.spyder-ide.org/current/installation.html#installing-with-conda)

#### Codio GUI:

[https://docs.codio.com/develop/develop/ide/boxes/installsw/gui.html](https://docs.codio.com/develop/develop/ide/boxes/installsw/gui.html)