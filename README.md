# Bias Evaluation Benchmark Dataset based on TIMIT

This repository contains two benchmark dataset variations for bias evaluation, originally created to evaluate bias in the Voice Privacy Challenge baseline systems [1]. 
The datasets can be useful for evaluating bias jointly for Automatic Speech Recognition (ASR) and Automatic Speaker Verification (ASV) systems. 

The benchmark datasets are based on TIMIT and were created using the algorithm proposed in [2].

Ten male and ten female speakers from each dialect were selected to ensure subgroup balance resulting in a total of 160 speakers.
One dataset consists of ten utterance pairs per speaker, i.e. five same and five different speaker pairs, resulting in 800 same speaker and 800 different speaker trials. 


[1] https://github.com/Voice-Privacy-Challenge
[2] Toussaint, W., Gorce, L., & Ding, A. Y. (2022). Design Guidelines for Inclusive Speaker Verification Evaluation Datasets. In Proceedings of the Annual Conference of the International Speech Communication Association, INTERSPEECH (Vol. 2022).
