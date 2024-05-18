# LLM

## Set up the Environment

### Create Conda Environment
```sh
# Create Conda environment
conda create -n py311 python=3.11
# Switch environment
conda activate py311
# Install ipykernel (if you want to use Jupyter in that environment)
conda install ipykernel
python -m ipykernel install --user --name=py311
# Checking
conda info --envs
jupyter kernelspec list


