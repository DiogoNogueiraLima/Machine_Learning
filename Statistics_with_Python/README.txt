# Make sure Conda is installed and set on system PATH

# List Conda Enviroments
conda info --envs

# Create local Enviroments
conda activate ./.venv. ### you can also pass the name

# ... or ... Create User Enviroment
conda create --name statistics_book

# Activate the Enviroment
conda activate statistics_book ### if you are having problems to acess the Enviroment, you must restart the Vscode and try to activate again

# Install Python
conda install python

# Select python interpreter on Vscode <ctrl+shift+p>

conda install --file requirements

### you should install this extension in the terminal on your enviroment (pingouin>=0.5.4) by yourself using the intruction below:
conda install -c conda-forge pingouin
