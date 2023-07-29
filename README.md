# SEED_emotion_recognition_with_transfer_learning
EEG based emotion recognition using Transfer Learning and CNN model on SEED, SEED-IV and SEED-V

To use this repo for classifying SEED, SEED-IV or SEED-V dataset:
1. dataset can be downloaded from: https://bcmi.sjtu.edu.cn/home/seed/ , with dataset owner's permission (you will have to mail dataset owner with License Agreement signed and they will provide you links to download). Usually if you want data for academic research purpose, you will get the data. I mailed them for database when I was doing my thesis work at NIT, bhopal (https://www.manit.ac.in/). Using your university mail will definitely help.
2. there are 3 folders, one for each SEED, SEED-IV and SEED-V.
3. each folder has two .ipynb files, one for featue extraction and one for training CNN from extracted features. First run the feature extraction code and you will be having extracted feratures persisted somewhere on disk.
4. use these features to train CNN and get classification done.
