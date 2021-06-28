# Bengali-digit-recognition-using-Hidden-Markov-Model
## INTRODUCTION
The aim of this project is to implement automatic speech recognition algorithms using Hidden Markov Models (HMMs) for Bengali languages. We have self-recorded Bengali digits From all over the State.
## LITERATURE REVIEW
Automatic Speech Recognition (ASR) is a well researched field. The utilization of HMMs for ASR is studied well in [A tutorial on hidden Markov models and selected applications in speech recognition](https://web.ece.ucsb.edu/Faculty/Rabiner/ece259/Reprints/tutorial%20on%20hmm%20and%20applications.pdf). The paper presents the core architecture of a HMM-based Large Vocabulary Continuous Speech Recognition (LVCSR) system and then describes ways to achieve state-of-the-art performance.

In the past few years, there has been significant work on developing speech recognition systems using HMMs for regional Indian languages. [In my work](https://github.com/Dibyendu1997/Bengali-digit-recognition-using-Hidden-Markov-Model/blob/main/Bengali%20Spoken%20Digit%20Classification_%20%20A%20Hidden%20Markov%20Model%20Approch.pdf) I use MFCC feature vectors and an acoustic HMM model to develop a recognition system for Bengali.
## DATASETS
The Bengali digits dataset consists of audio files recorded in ‘.wav’ format. Each file contains the utterance of one Bengali digit from 0-9. The length of each file is approximately 1.5 second. A total of 600 samples are present with each digit having around 60 samples. The dataset can be accessed [here](https://drive.google.com/drive/folders/1SjbwqcdW0JqHlrs08FsKfudFhHk7K6f7?usp=sharing)
The digit-label-utterance mapping is given in the following table.

Digit | Label | Utterance
----- | ----- | ---------
Zero | 0 | Sunno
One | 1 | Aek
Two | 2 | Dui
Three | 3 | Tin
Four | 4 | Char
Five | 5 | Pach
Six | 6 | Chhoy
Seven | 7 | Shat
Eight| 8 | At
Nine | 9 | Noy

## **Training Results**

We trained the model on 478 samples by shuffling the samples. The model was trained for 100 epochs.

* Total number of train samples = 478
* Accuracy = 95.5%

## **Testing Results**

We trained the model on 478 samples by shuffling the samples. The model was trained for 100 epochs.

* Total number of test samples = 122
* Accuracy = 75.5%
