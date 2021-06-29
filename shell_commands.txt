# Setting up your workspace
# Initialize conda
conda init

# Shorten the command prompt
echo "PS1='\w $ '" >> .bashrc

# Update for changes to take place
source .bashrc

## Note you could also restart the terminal for the same effect

#Viewing a list of your environments
conda info --envs
or
conda env list

#First, create your environment and activate it:
conda create -n test-env
or
conda create --name myenv

#activate it:
conda activate test-env

#deactivate it:
conda deactivate
