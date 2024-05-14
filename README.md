# NYU-ECE-GY-7123-Deep-Learning-Final-Project
Ziyi Huang(zh2931), Shuning Li(sl10916)

## Overview
This is the code base for our final project titled `'Transformer-based Recommender System and Transfer Learning'`. In this project, we reconstructed an SSE-PT model for recommender system as described in this paper: https://dl.acm.org/doi/pdf/10.1145/3383313.3412258 and pre-trained it on the MovieLens-1M dataset (dataset can be found in the `./data` folder along with some other datasets, including the target dataset for transfer learning). Then, we did a transfer learning and fine-tuned the trained model on the Wiki1000 dataset ('wikipedia.txt' in the data folder) The code is an adaption of this repository: https://github.com/pmixer/SASRec.pytorch/tree/master, which is a pytorch implementation of the SASRec model (base model of SSE-PT), also with reference to the following repos: https://github.com/recommenders-team/recommenders/blob/main/examples/00_quick_start/sasrec_amazon.ipynb
https://github.com/wuliwei9278/SSE-PT/tree/master



There are two `.ipynb` files in the codebase:
-- The main training notebook used for training is `DL_final_projce.ipynb`, which has all the setup of our model for pre-train and fine tuning, with result displayed.
-- A second auxillary notebook used for data processing raw data of MovieLens-100K and Lastfm-1K-User datasets downloaded from the web - they were our inital planned training and target dataset for the project.
