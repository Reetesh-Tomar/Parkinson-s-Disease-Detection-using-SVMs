# Parkinson-s-Disease-Detection-using-SVMs
Built a machine learning system to detect whether a person is Parkinsons positive or not using Support Vector Machine model

Parkinson's disease- 
It is a progressive nervous system disorder that affects movement leading to shaking, stiffness, and difficulty with walking, balance, and coordination. Parkinson's symptoms usually begin gradually and get worse over time

Workflow-
    Parkinson's Data  ---->  Data pre processing  ---->  Train Test and Split  ---->  Support Vector Machine Classifier
   
    New Data  ---->  Trained SVM classifier  ---->  Prediction of disease

About Dataset used-
    I have used Parkinson's dataset that is given on kaggle.com site and freely available.
    
    About dataset-
    This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease (PD). 
    Each column in the table is a particular voice measure, and each row corresponds one of 195 voice recording from   
    these individuals ("name" column). The main aim of the data is to discriminate healthy people from those with PD, 
    according to "status" column which is set to 0 for healthy and 1 for PD.
    
    Attribute Information:

    Matrix column entries (attributes):
    name - ASCII subject name and recording number
    MDVP:Fo(Hz) - Average vocal fundamental frequency
    MDVP:Fhi(Hz) - Maximum vocal fundamental frequency
    MDVP:Flo(Hz) - Minimum vocal fundamental frequency
    MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several
    measures of variation in fundamental frequency
    MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude
    NHR,HNR - Two measures of ratio of noise to tonal components in the voice
    status - Health status of the subject (one) - Parkinson's, (zero) - healthy
    RPDE,D2 - Two nonlinear dynamical complexity measures
    DFA - Signal fractal scaling exponent
    spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation

Support Vector Machine Model
     SVM models can be used for both classification and regression problems, but in our case we are using it for
     classification of whether a person is PD positive or negative
