# Speaker-Identification-Using-Ensemble-Learning-Approach-Considering-CNN-As-Feature-Extractor
Speaker Identification Using Ensemble Learning Approach Considering CNN As Feature Extractor

# 
Cite this paper

Dhar, S., Phukan, S., Gogoi, R., Jana, N.D. (2023). Speaker Identification Using Ensemble Learning With Deep Convolutional Features. In: Das, S., Saha, S., Coello Coello, C.A., Bansal, J.C. (eds) Advances in Data-driven Computing and Intelligent Systems. Lecture Notes in Networks and Systems, vol 653. Springer, Singapore. https://doi.org/10.1007/978-981-99-0981-0_9

Paper Link: https://link.springer.com/chapter/10.1007/978-981-99-0981-0_9

1. code file (in .ipynb format) of Audio Data Augmentation (file: Audio_data_augmentation).
2. code file (in .ipynb format) of Mel Spectrogram Generation from audio data (file: Mel_Spectrogram_Generation).


# **Datasets:**

Input audio data are available in the given google drivelink provided below:

#### 1. VCC2016 Dataset 
  
    https://drive.google.com/drive/folders/1LT13hS3DqBTEjwyZ5l_88Z1pcU8kYpa0?usp=sharing
    
This folder contains audio files of 4 speakers.
    
#### 2. VCC2020 Dataset

      https://drive.google.com/drive/folders/1dy27QHZ-P7Db_1C1nHG3quL3lR1ux0Nj?usp=sharing
      
  This folder contains Audio files of 4 speakers.
      
   Where 2nd Letter of the folder refers the language.
   
* E - English
* F - Finnish
* G - German 
* M - Mandarin 
      
      
Where 3rd Letter of the folder refers the gender.
   
* F - Female
* M - Male
      
#### 3. Augmented Audio Data
    
  Due to the limited audio data of the VCC2020 Dataset, we have performed augmentation on it. Generated Audio datas are available in the given link provided below:

   
    https://drive.google.com/drive/folders/1G3e2JFcDB0z6AETe3teJNlR3UnH4TCTS?usp=sharing
    
  Three audio augmentation techniques are applied to generate these data:
    
  * Pitch Scale
  * Random Gain
  * Invert Polarity


#### 4. VCC2020 Merge Dataset
      
    https://drive.google.com/drive/folders/1owS6Ml9onVOP9K_peZFGqlqszjVFlxZG?usp=sharing
    
 We have prepared this dataset by merging data from the original VCC2020 dataset and augmented data.
 
 
#### 5. Generated Mel Spectrogram

  A) From VCC2016 Dataset
  
        https://drive.google.com/drive/folders/1zo_ObMLI2CXTd1mV8_62U6iwCBRo8jmY?usp=sharing
        
  B) From VCC2020 Merge Dataset
  
      https://drive.google.com/drive/folders/1u2aov4Ykw3QUI50V6M9Ho9K9-OLoPzL3?usp=sharing
      
  C) From Emotional Dataset
  
      https://drive.google.com/drive/folders/1lZiIDj7I7HWhFzr0Y74i-bULKQq4ta22?usp=sharing
    
    
#### PPT regarding the data preprocessing:

https://docs.google.com/presentation/d/1xlOfgeGpcYqbxfGoHROtlb6ngwmFzjGbNEj8__Hz4B0/edit?usp=sharing
