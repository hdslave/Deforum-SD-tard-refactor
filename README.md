LINUX INSTRUCTIONS
-------------------------------------------
open terminal - ctrl alt T

git clone this fork

cd to downloaded directory

conda env create -f environment.yaml 

conda activate d3d

pip install  torch, torchvision, omegaconf, einops, pytorch-lightning, torchmetrics, torchtext, transformers, kornia, IPython 

git clone https://github.com/deforum/stable-diffusion

pip install -e git+https://github.com/CompVis/taming-transformers.git@master#egg=taming-transformers

pip install -e git+https://github.com/openai/CLIP.git@main#egg=clip

pip install accelerate, ftfy, jsonmerge, matplotlib, resize-right, timm, torchdiffeq

git clone https://github.com/isl-org/MiDaS.git

git clone https://github.com/MSFTserver/pytorch3d-lite.git

download sd-v1-4.ckpt & dpt_large-midas.pt files and put them in content/models  directory

edit Deforum_Stable_Diffusion.py with text editor to enter prompt where it lists it, use deforum google collab notebook as a guide to find the parameters

python3 Deforum_Stable_Diffusion.py
