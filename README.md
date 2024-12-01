# Speech to Sign
![speechtosign3](https://user-images.githubusercontent.com/84968542/229211470-44aa8cf8-f46c-44de-99c8-a2a96e47eaad.png)

The main aim of our project is to create an application that can translate speech to sign language. Sign Language is one  of the most important and widely used forms of communication for people with speaking and hearing impairments. Although many individuals and groups have made an effort to develop systems that read sign language symbols and translate them into text, there are very few instances of text or audio being converted into sign language. The primary goal of this project is to create a translating system made up of numerous modules that accept English audio input and convert that to English text using RNN, CNN, and CTC loss.
# Technology
CNN<br />
RNN
# Language
Python
# ML Code
The code takes an audio file as input and gives out the predcited text output. 
The below shown image is the results obtained after training and testing the model.

<img width="633" alt="image" src="https://user-images.githubusercontent.com/84968542/229286356-77b8a88f-70ea-4e20-9143-cd2ccdd4a2b1.png">

# Text to Sign
This converts the predicted text output into sign language. The text is parsed to create a structured grammar representation, on which Sign Language grammar rules are applied.
# Application
The starting dataset was obtained from LJSpeech Dataset. The aim was to get better datasets and optimize the model by changing various parameters. The model also takes live audio input from the user and converts it to .wav format which will be used for speech-to-text conversion.
The result for the application has been included below.


https://user-images.githubusercontent.com/84968542/229286867-b9669fac-3300-402d-b85d-80f7e42b01ee.mp4


