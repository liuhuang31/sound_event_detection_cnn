# CNN based DCASE 2016 sound event detection system 
The original code is here https://github.com/gorinars/dcase16-cnn 

Because the original code has some problem, which i changed some places to make it works.

## First, you should install the requirements which in requirements.txt
If can't run the following commands,maybe the version of keras is too high.
You can use the provided file :Keras-1.2.2.tar.gz.

## Basic usage

*run-cnn-pipeline.sh* - complete self-documented script for reproducing all the experiments including the following:

  * *task3_gmm_baseline.py* - baseline GMM system [provided](https://github.com/TUT-ARG/DCASE2016-baseline-system-python) by organizers.

  * *src/make_downsample.sh* - basic data preparation (down sampling)

  * *task3_cnn.py* - run CNN based system training and testing

  * *src/make_speed.sh* - speed perturbation
