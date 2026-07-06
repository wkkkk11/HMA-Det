# HMA-Det: Heterogeneous Modality-Aware Optical-SAR Detection Framework for Remote Sensing Ship Detection

## Installation

conda create -n hma python=3.8

conda activate hma

pip install -r requirements.txt

## Training

python train.py --data MOS-Ship.yaml --epochs 100 --batch 16

## Testing
python val.py --weights best.pt --data MOS-Ship.yaml
