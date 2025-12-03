# Abonti-Digit-Recognition-System
**This project implements an automatic spoken digit recognition system using Hidden Markov Models (HMMs).
It supports both pre-recorded audio testing and live recording-based testing, with separate modules for training and testing.**

Features
1. Training Module

                  Uses HMM to train acoustic models for digits 0–9

                  Uses 30+ utterances per digit

                 Extracts MFCC features from training audio files

                 Builds 10 HMM models, one for each digit

                Stores model parameters (A, B, π) for future testing

2. Testing Module
                             A. Pre-Recorded Audio Testing

                                Takes pre-recorded test files

                                Performs feature extraction

                                Computes HMM 

                                Identifies the digit with the maximum probability

                               Calculates overall accuracy after testing all files

B. Live Recording Testing

Takes voice input through microphone

Extracts MFCC

Compares against the trained models

Displays the recognized digit



