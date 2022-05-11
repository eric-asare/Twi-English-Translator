# Politics of Code Final Project

## my-Twi-English-translator
I made an English to Twi translator. my-Twi-English-translator is an NLP python program that translates an  English Text to Twi. 


Twi is one of the major Ghanaian Languages. 
NLP (Natural Language Processing) is a subset of Machine Learning and AI concerned with teaching computers to read, understand and act on human language. 

I have always desired a translator for myself because I love speaking my mother tongue but did not know how to go about building one.

There is no perfect Google translation for any of the Ghanain languages. There is none for Twi. 

<p align="center">
  <img 
    width="450"
    height="300"
    src="https://github.com/eric-asare/my-Twi-English-translator/blob/main/image/Screen%20Shot%202022-05-11%20at%2011.59.34%20PM.png"
  >
</p>

 
Ghana NLP Open AI is kasa which in the Akan language means "Talk" or "Speak". This AI is been built to provide a wide range of NLP tools for summarizing , classifying text, language dection and voice to text operations. 

In building this applications, I read a lot of blogs on NLP. The tech Stack I used was Python and Google Collab. Google Collab is like jupiter notebook hosted by Google. It gave me a free GPU for training data. 

I initally started with the model mt5 because of its ability to track previous sentences as it provides translation for the word. 

All the models I found including `mt5` only served foreign languages like  French not Twi

Eventually, I found https://huggingface.co/Helsinki-NLP

Helsinki had been pretrained on some Twi

I loaded the model and tokenizer, I take an english sentence as input from the user and show the translation. 

my-Twi-English-translator is important because without a translation tool, people interested in Ghanain language whether a ghanain or foreigner cannot learn since there is no tool to help with translation. Health workers and people in humanitarian aid who want to reach people in other areas of Ghana who do not speak their language cannot help due to the language barier. 

AI and Machine learning is becoming increasing important for national security and cultural representation. 

Increase in text data is beyond human analysis. From medical diagnoses, financial system interfaces, translation system and cybersecurity hence the need for programs to understand and process texts well. Hence the need to build tools to understand data person. 



References
https://medium.com/swlh/ghana-nlp-computational-mapping-of-ghanaian-languages-edf60c56bcce

mt5 model : https://huggingface.co/docs/transformers/model_doc/mt5

Transfomerer : https://www.kaggle.com/code/azunre/tlfornlp-chapter7-transformer







