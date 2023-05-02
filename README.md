# ML_Final-project

# teammates’ GitHub account name: 

jxu156

# contribution: 

1. Writring report 

2. Prepare Presentation PPT

3. Modify the network

#Dataset download

Images can be downloaded from here: 

https://drive.google.com/file/d/1ymDYrGs9DSRicfZbSCDiOu0ikGDh5k6S/view?usp=sharing

Precomputed density maps can be found here: https://archive.org/details/FSC147-GT

Place the unzipped image directory and density map directory inside the data directory.

#Quick demo

Provide the input image and also provide the bounding boxes of exemplar objects using a text file:

python demo.py --input-image orange.jpg --bbox-file orange_box_ex.txt 

#Evaluation

##Testing on validation split without adaptation

python test.py --data_path /PATH/TO/YOUR/FSC147/DATASET/ --test_split val

##Testing on val split with adaptation

## Other ways to do multiple ways for testing

just refer to the report






python test.py --data_path /PATH/TO/YOUR/FSC147/DATASET/ --test_split val --adapt

##Training

python train.py --gpu 0




