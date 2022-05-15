# Politics of Code Final Project

## my-Twi-English-translator
I made an English to Twi translator. my-Twi-English-translator is an NLP python program that translates an  English Text to Twi. 

Link to Google Collab : https://colab.research.google.com/drive/1T5L9iVa8UAzAO9C_aASBb8AWC8ZEkt2z?usp=sharing

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

What is your opinion of Google Translate? Is your language supported by Google? Would you like to introduce your native language to friends? Have you ever wondered how Google Translate works? I have also wondered about these questions, and I became fascinated by them. That's when I came across NLP. It is Natural Language Processing. It is how Google Translate, for example, can understand your language, whether it's written or spoken. A few days ago, Google began supporting Twi in Google Translate. It was amazing to me how software could handle such a complex language. After researching online and playing around with some models, I will explain what machine language translation is and give you a link to a simple demo. Translation employs a neural network. Think of a neural network as a vending machine where you insert money to get the item corresponding to the price. In the case of translation, the neural network generates a translation based on the input. There is a mapping from one language to another. Neural networks can be standard or recurrent. Standard neural networks output word-for-word every time. Recurrent, on the other hand, look for context based on the previous word. Suppose a language has the structure "Eric, he is a boy" - a standard neural network would produce Eric, he is a boy, while a recurrent neural network would produce Eric is a boy. It does not seem problematic on a small scale, but there are some languages in which translating each word without referring to previous words can lead to really bad translations. The full translation pipeline requires you to normalize the text input by the user so that different capitalizations of words are always encoded the same way. For example, APPLE, and apPLe should all be normalized to Apple so that the neural network can understand. You can now pass the normalized text through a machine learning algorithm or framework. When it comes to NLP, it's good to know there are a lot of machine learning models that you can try out. Marian Natural Machine Translation (MNT) is a good example. Now you need a powerful computer with Linux, a GPU, and high CPU performance, but this shouldn't stop you from experimenting. Creating software tools to solve such challenging problems is one of the reasons I enjoy Computer Science. The only thing you need to get these high CPU and GPU performance is a Kaggle editor or Google Collabs, which are free and available to everyone. After you have a platform, you can decide whether to train your model or use a pre-trained one. Since training a new model might take many days, you can experiment with a pre-trained model. These models are simple to understand and use. If you get lost, documentation is usually available. A link to me trying out the Helsinki NLP model to translate from English to Twi. https://colab.research.google.com/drive/1T5L9iVa8UAzAO9C_aASBb8AWC8ZEkt2z?usp=sharing





References
https://medium.com/swlh/ghana-nlp-computational-mapping-of-ghanaian-languages-edf60c56bcce

mt5 model : https://huggingface.co/docs/transformers/model_doc/mt5

Transfomerer : https://www.kaggle.com/code/azunre/tlfornlp-chapter7-transformer







