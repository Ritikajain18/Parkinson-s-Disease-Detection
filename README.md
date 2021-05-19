# :brain: Parkinsons Disease Detection
The objective of this project is to detect the presence of Parkinson’s disease in a human using various Machine Learning Algorithms at an early stage to halt the further progression of this deadly disease.

## Motivation
Machine learning and its applications have paved their way into healthcare and has proved itself by showing remarkable results in this field. One of the major areas of its applications is the detection of Parkinson’s disease which is a brain disorder that appears due to the disruption of brain cells that produce dopamine. When these brain cells reach their threshold limit, symptoms of PD start appearing. The disease may begin years before the motor and non-motor symptoms of this disease appear so early detection of this disease is necessary to layoff the further progression of this disease. 

## Tech/Framework Used
- Python
- Feature extraction
- Machine learning/Deep Learning

## Features
The proposed methodology extracts ten features from the vocal recordings namely:

-MDVP:Fo(Hz)	- Average vocal fundamental frequency
-MDVP:Fhi(Hz)	- Maximum vocal fundamental frequency
-MDVP:Flo(Hz)	- Minimum vocal fundamental frequency
-MDVP:Jitter(%),MDVP:Jitter(Abs), MDVP:RAP,MDVP:PPQ,Jitter:DDP	- Several measures of variation in fundamental frequency
-MDVP:Shimmer,MDVP:Shimmer(dB), Shimmer: APQ3, Shimmer: APQ5, MDVP:APQ,Shimmer:DDA	- Several measures of variation in amplitude
-NHR, HNR	    - Two measures of ratio of noise to tonal components in the voice
-status       - Health status of the subject (one) - Parkinson's, (zero) - healthy
-RPDE, D2	    -Two nonlinear dynamical complexity measures
-DFA	        - Signal fractal scaling exponent
- spread1, spread2, PPE	 - Three nonlinear measures of fundamental frequency variation

## Dataset reference
The dataset which has been used for the analysis has been obtained by Max Little of the University of Oxford, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals. This dataset was given to UCI Machine learning Repository, Center for Machine Learning and Intelligent Systems. The dataset consists of biomedical voice measurements of 31 people, out of which 23 have Parkinson’s disease. Each column in the relation is a voice measure and each row corresponds one of 195 voice recording from individuals.
