# conda-keeper
A custom shell script to invoke / restrict the conda command.
[intented to make ROS and anaconda together]

You may want to change the ANACONDA_PATH in conda-keeper.sh to your local path to anaconda binaries.

[How to setup]
cd ~
git clone https://github.com/jwchoi9303/conda-keeper
chmod +x ~/conda-keeper/conda-keeper.sh
echo 'source ~/conda-keeper/conda-keeper.sh' >> ~/.bashrc

[How to use]
'hey-conda' adds the $ANACONDA_PATH(=${HOME}/anaconda2/bin) to $PATH
'bye-conda' removes the $ANACONDA_PATH from $PATH

So, basically, the idea is that if you want to work with ROS say bye-conda,and if you want to work with conda or anaconda-navigator say hey-conda.
