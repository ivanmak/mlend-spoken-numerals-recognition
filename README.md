# mlend-spoken-numerals-recognition

## Introduction
This repository contains the deliverable of the mini-project of the course ECS708 Machine Learning at Queen Mary University of London, in the Spring semester of 2021.

The purpose of the mini-project was to create a machine learning model that can recognise different spoken numerals. It consists of two parts, a basic part (compulsory for all student) where intonation was predicted, and an advanced part where there was no set-and-stone scope. In my work, randomly sequence of the spoken numerals were generated from the dataset, and a model was built in attempt to identify the spoken numerals.

The work was in one single Jupyer notebook, including exploratory data analysis, the basic solution (identifying intonations), the advanced solution (identifying a random sequence of spoken numerals), and discussion of the results.

Neural network was used in the mini-project in both basic and advanced solutions of the coursework, using tensorflow-keras. Keras-tuner was also used to further fine-tune the neural networks.

## Dataset
Students of the course contributed to a completely new dataset, which contains labelled audio recordings of numerals read in English.

The spoken numerals contain:
- Ones sequence: zero, one, two, three, four, five, six, seven, eight, nine.
- Teens sequence: ten, eleven, twelve, thirteen, fourteen, fifteen, sixteen, seventeen, eighteen, nineteen.
- Large sequence: twenty, thirty, forty, fifty, sixty, seventy, eighty, ninety, hundred, thousand, million, billion.

Each student recorded each numeral using four different intonation twice:
- Neutral
- Bored
- Excited
- Question

The dataset will be made public by the course organiser in the future.

## Environment
The coursework was done on the following environment:
- Google Colab
- Python 3.7
- numpy==1.19.5
- pandas==1.1.5
- tensorflow==2.4.1
- Keras==2.4.3
- keras-tuner 1.0.2
- pydub 0.25.1

## References
- [https://www.tensorflow.org/tutorials/audio/simple_audio](https://www.tensorflow.org/tutorials/audio/simple_audio)
- [https://dataunbox.com/split-audio-files-using-python/](https://dataunbox.com/split-audio-files-using-python/)