# cadn_asapy

conda create -n asapy --yes ipykernel nb_conda_kernels python==3.9
conda activate asapy
conda install -r ./requirements.txt
jupyter lab --no-browser