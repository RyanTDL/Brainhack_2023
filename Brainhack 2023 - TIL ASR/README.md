# TIL2023 ASR Qualifiers Challenge - RYANSLAVES

The TIL2023 CV Qualifiers code

## Setting up the environment

### Platform

Run the code using Noteable Platform  

* Create a new project.
* Give the project a name and (optionally) a description.
* Download `Brainhack 2023 - TIL ASR.zip` provided in form into local directory.
* Unzip .zip file in local directory.
* Create a new folder of the same name in Noteable.
* Drag all files from local directory folder into the folder created in Noteable.
* Open `ASR Model Code - freqtimemasking(30,100)_clayers5_rlayers7.ipynb` on Noteable.


### Install requirements

To install the requirements, run the following commands in `ASR Model Code - freqtimemasking(30,100)_clayers5_rlayers7.ipynb` on Noteable:

```shell
!pip install tqdm==4.65.0
!pip install jiwer==3.0.1   
!pip install librosa==0.9.1
!pip install pandas==2.0.0rc

# check versioning of torch and pandas
# check that torch is 2.0.1 and torchaudio is 2.0.2
!pip list | grep -E 'torch|pandas'
``` 

## Running the code

### Model Training & Inference  
To train a model, modify the directory where you saved the data and the corresponding annotation file. Run all commands in `ASR Model Code - freqtimemasking(30,100)_clayers5_rlayers7.ipynb` on Noteable.

## Final Submission File

* `Submission_Advanced-freqtimemasking(30,100)_clayers5_rlayers7.csv` file that results in the final reflected private score.

## Model Weight File

Cannot be saved in Noteable due to it being a large file exceeding 100MB. 