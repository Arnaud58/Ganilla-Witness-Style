# Ganilla

**Paper:** https://arxiv.org/abs/2002.05638

**Network** https://github.com/giddyyupp/ganilla

## Content

This repo contain my own model train with ganilla. The goal is to test the ganilla network on custom datasets to transform a [landscape](https://www.kaggle.com/arnaud58/landscape-pictures) pictures into [*the witness game*](https://www.kaggle.com/arnaud58/the-witness) style. The two datasets are on kaggle and are create by myself.

To use the model in the folder *landscape2witness* you must to download [the PyTorch github repo](https://github.com/giddyyupp/ganilla) and execute the command : 

``python test.py --dataroot ./datasets/landscape2witness --name landscape2witness --model cycle_gan --netG resnet_fpn --batch_size 4 --epoch 100``

Here exemple of results pictures :

## Landscape to witness


Landscape photo | Witness style
 --- | --- 
![REAL_A1](images/00000052_(3)_real_A.png) | ![FAKE_B1](images/00000052_(3)_fake_B.png) 
![REAL_A2](images/00000470_(5)_real_A.png) | ![FAKE_B2](images/00000470_(5)_fake_B.png) 
![REAL_A3](images/60467816_2160165764295949_889770228475494400_o_real_A.png) | ![FAKE_B3](images/60467816_2160165764295949_889770228475494400_o_fake_B.png) 
![REAL_A4](images/00000454_(4)_real_A.png) | ![FAKE_B4](images/00000454_(4)_fake_B.png) 
![REAL_A5](images/00000089_(5)_real_A.png) | ![FAKE_B5](images/00000089_(5)_fake_B.png) 
![REAL_A6](images/IMG_8401_real_A.png) | ![FAKE_B6](images/IMG_8401_fake_B.png) 
## Witness to landscape

Witness Game picture | "Realist" style
 --- | --- 
![REAL_B1](images/00000052_(3)_real_B.png) | ![FAKE_A1](images/00000052_(3)_fake_A.png) 
![REAL_B2](images/IMG_1170_real_B.png) | ![FAKE_A2](images/IMG_1170_fake_A.png) 
![REAL_B3](images/IMG_1570_real_B.png) | ![FAKE_A3](images/IMG_1570_fake_A.png) 
![REAL_B4](images/60467816_2160165764295949_889770228475494400_o_real_B.png) | ![FAKE_A4](images/60467816_2160165764295949_889770228475494400_o_fake_A.png) 
![REAL_B5](images/IMG_7970_real_B.png) | ![FAKE_A5](images/IMG_7970_fake_A.png) 
![REAL_B6](images/IMG_8555_real_B.png) | ![FAKE_A6](images/IMG_8555_fake_A.png) 
