### Creating an environment with commands
By default, environments are installed into the `envs` directory in your conda directory.

- Use the terminal or an Anaconda Prompt for the following steps:
  1. To create an environment: `conda create --name myenv`
  2. When conda asks you to proceed, type `y`: `proceed ([y]/n)?`
  
  This creates the myenv environment in `/envs/`. No packages will be installed in this environment.

---

### Activating an environment
* To activate an environment: `conda activate myenv` [^1]
[^1]: Replace `myenv` with the environment name or directory path.

---

### Viewing a list of your environments
* To see a list of all of your environments, in your terminal window or an Anaconda Prompt, run:
`conda info --envs` OR `conda env list`