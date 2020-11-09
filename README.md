# Forest Cover Type Problem

To solve the Forest Cover Type Problem (Kaggle.com, 2019), the goal is to predict an integer classification for the forest cover type (the predominant kind of tree cover) from strictly cartographic variables (as opposed to remotely sensed data). The actual forest cover type for a given 30 x 30 meter cell was determined from US Forest Service (USFS) Region 2 Resource Information System data. Independent variables were then derived from data obtained from the US Geological Survey and USFS. The data is in raw form (not scaled) and contains binary columns of data for qualitative independent variables such as wilderness areas and soil type. This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices. The seven types are:

1 - Spruce/Fir
2 - Lodgepole Pine
3 - Ponderosa Pine
4 - Cottonwood/Willow
5 - Aspen
6 - Douglas-fir
7 - Krummholz

The dataset (15120 observations) contains both features and the Cover_Type. We will split the dataset into 80% for training testing and 20% as unseen data for predicting.

Contents
1 Introduction
2 Data Preprocessing
2.1 Raw data and structure analysis 
2.2 Dataset preparation
2.3 Data transformation 
2.4 Data visualization
    2.4.1 missing value
    2.4.2 outlier
2.5 Feature Engineering
2.6 Normalization
3 Analysis, Results and Discussion
3.1 Methods and Algorithms used
3.2 Experimental Process
3.3 Results and Discussion
4 Evaluation on unseen data
5 Conclusion and Future work
Claim 1: The models we choose provide a good enough mean accuracy of about 80% for ‘data B’ which has only 6 features (i-e extracted by us) and is as half the number of original transformed dataset ‘Data A’. Next, we do optimization for selected models i-e Random Forest and ExtraTree classifier.

Claim 2: Based on all the results and prediction accuracy discussed, we can claim that we are confident that our model can do good predication for 5 cover Types from 7 excluding cover Type 1 and 2.
