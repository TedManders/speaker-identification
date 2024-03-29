# Deep Learning Challenge: Speaker Identification

## Introduction
This challenge was part of the Deep Learning course (2022) at Tilburg University. The task aims at labeling spoken utterances with an ID of one of the 183 unique speakers. The raw training data contains WAVE files, which are processed to be used as input to a deep learning model.

### Result
Our team got second place out of a total of 40 teams with a test error rate of 0.0122 (98.78% accuracy).

### Report & Code
Find our task report in .pdf format and code in .py format on this page, to read more about the approach in detail.

## Approach
A Convolutional Neural Network (CNN) was used with WAVE sound files converted to Mel-frequency cepstrum (MFCC) as input. The Python code for the CNN model was based on a model by Doshi (2021).

## Dataset
The data folder contains a training folder with 30.000 samples and a test folder with 10.000 samples. A separate JSON file with 30.000 ID's and corresponding labels was available for the training data.

## Evaluation
The evaluation metric for this task was mean error rate, or the percentage of incorrect labels. The predicted test set labels were evaluated after submission to a private competition server on Codalab.

## Sources
D. Harwath and J. Glass, "Deep Multimodal Semantic Embeddings for Speech and Images," 2015 IEEE Automatic Speech Recognition and Understanding Workshop, pp. 237-244, Scottsdale, Arizona, USA, December 2015 (PDF)

M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artificial Intelligence Research, Volume 47, pages 853-899 https://www.jair.org/index.php/jair/article/view/10833/25854

Doshi, K. (2021) Audio Deep Learning Made Simple Sound Classification, Step-by-Step. Towards Data Science. https://towardsdatascience.com/audiodeep-learning-made-simple-sound-classification-stepby-step-cebc936bbe5 

Ye, F., & Yang, J. (2021). A Deep Neural Network Model for Speaker Identification. Applied Sciences, 11(8), 3603.
