open terminal - ctrl alt T

git clone this fork

cd to downloaded directory

conda env create -f environment.yaml 

conda activate d3d

pip install  torch, torchvision, --extra-index-url, https://download.pytorch.org/whl/cu113, omegaconf==2.2.3, einops==0.4.1, pytorch-lightning==1.7.4, torchmetrics==0.9.3, torchtext==0.13.1, transformers==4.21.2, kornia==0.6.7, IPython, 

git clone https://github.com/deforum/stable-diffusion

pip instalL -e git+https://github.com/CompVis/taming-transformers.git@master#egg=taming-transformers

pip install -e git+https://github.com/openai/CLIP.git@main#egg=clip

pip install accelerate, ftfy, jsonmerge, matplotlib, resize-right, timm, torchdiffeq

git clone https://github.com/isl-org/MiDaS.git

git clone https://github.com/MSFTserver/pytorch3d-lite.git

download sd-v1-4.ckpt & dpt_large-midas.ckpt files and put them in content/models  directory
