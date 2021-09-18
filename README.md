# Speech Synthesis for Low Resource Languages using Transliteration Enabled Transfer Learning

Work Done by Vineet Bhat, under the guidance of Prof Pushpak Bhattacharyya, Department of Computer Science, IIT Bombay


## Abstract 

In the area of Human Computer Interaction ( HCI ), Text To Speech (TTS) synthesis has received a significant boost in recent years, especially with the development of various deep learning techniques capable of generating excellent quality speech.  However, deep learning demands a vast quantity of data, with speech recognition and synthesis systems requiring more than thousand hours of aligned corpus to train end-to-end systems. While a large amount of data is available in open-source for  \emph{high resource languages} such as English, Spanish, and Italian, the majority of languages like Asian and  African  have little to no training data. To develop good speech synthesis systems in these \emph{ low resource} languages, we need innovative ideas based, for example, on transfer learning and knowledge-sharing. This paper gives a novel method for doing TTS through transliteration activated transfer learning, an intuitive yet powerful method to boost the learning process in speech synthesis. Transliteration is essential in transferring phonetic information from one language to another. By incorporating this method in a novel speech synthesis pipeline, we demonstrate accelerated training and improved speech quality. We show the efficacy of fine-tuning the pretrained models- trained on high resource languages- on the smaller annotated corpus of low resource language to jumpstart the training process. Our approach received an average Mean Opinion Score of 4.65 out of 5 based on a survey of 100+ persons, which is better than State of Art transfer learning based speech synthesis systems. We also make our code and data available.

## Steps to Run this project 

 * _Training the TTS system for Hindi (or Marathi)_ - refer to TTSModelHindi.ipynb for detailed instructions 
 * _Demo for TTS System for Hindi (or Marathi)_ - refer to TTSInferenceHindi.ipynb for detailed instructions


## Results of the Project

This presentation contains the overview as well as the results of the project - https://docs.google.com/presentation/d/1B1GMukRFSvsvdGES-ELk0_rRJ3dmCsK2o3qVzNmj3_4/edit?usp=sharing
