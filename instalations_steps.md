## Instalar Conda
https://docs.conda.io/projects/conda/en/stable/user-guide/install/linux.html

## Instalar ambiente LaSAFT
conda env create -f lasaft_env_gpu.yaml -n lasaft

## Ativar conda LaSAFT
conda activate lasaft

## Alterar pip para versao <= 24.0
pip install pip==24.0

## Instalar restantes requisitos pip
pip install -r requirements.txt