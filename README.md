# pd_pose_2_UDysRS]


This repo will act as my testing bed. The goal of this project is to convert limb position data retrieved from pose estimation and convert that to UDysRS classes for each limb. 

1st experimement
----------------------

convert right wrist position data to spectrograms and classify the spectrograms in to UDysRS ratings

experiment file: experiment_1/PD_VGG.ipynb (viewable on colab)
requirements file: experiment_1/requirement.txt

2nd experiment
----------------------

The data for each experiment trial (such as communication, drinking) contains the positon data for each limb. 

The idea:
Convert all limb position data to spectrograms
Merge the spectrograms to one image
classify the combine image into a list of UDysRS ratings for each limb 
