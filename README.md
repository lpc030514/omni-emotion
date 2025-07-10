# omni-emotion
offical code for omni-emotion via reinforce learning
```
conda create -n r1-v python=3.11 
conda activate r1-v
pip install modelscope
modelscope download --model AI-ModelScope/whisper-large-v3
modelscope download --model AI-ModelScope/bert-base-uncased
modelscope download --model AI-ModelScope/siglip-base-patch16-224
modelscope download --model iic/EMER-SFT-0.5B

cd src/r1-v 
pip install -e ".[dev]"
pip install qwen_vl_utils torchvision
pip install moviepy
pip install timm
pip install numpy==1.26.4
pip install opencv-python==4.10.0.82
pip install decord
pip install wandb
pip install ipdb
pip install h5py
cd /home/featurize/work/R1-Omni/src/r1-v

pip install wandb
bash run_grpo_humanomni.sh
```
