Recreate Python Environment:
conda create --prefix ./prototype_a_conda  python=3.11 (I used this to create it)
conda activate /Users/neilgawande/ONEAPE/TheChain/prototype_a/prototype_a_conda
conda deactivate

Save and Export Conda Environment -> conda env export > environment.yml

There is a way to recreate the environment form the environment.yml file.