# Neural-Machine-Translation

Several sources have been used  for the literature survey, ranging from research papers of IEEE, SPRINGER, ACM to various journals and papers of international conferences in formulating the problem statement. Also,  various articles and followed blogs available online for a better and in-depth understanding of the topic have been used.

In large societies like India there is a huge demand to convert one human language into another. This project focuses on designing a system that translate the document from english to hindi with reference to the meaning and with in the context of the document  with the word sense disambiguation which helps identifying the proper sense of ambiguous words in text. 
Main focus of the project is on improving the accuracy with the help of neural machine translation methods. We will compare different algorithms and find which method gives us the best result. The algorithm includes Sequence to Sequence model Recurrent Neural Network,LSTM neural network architecture with and without attention mechanism. It involves applying True Text techniques to eliminate quirks in the data. We scrubs the data of natural pauses, incomprehensible words and repetitions so that the text format is more readable by the neural network using word embedding algorithms (GLOVE, WORD2VEC).


Empirical Study- 
Several neural networks models have been used to train dataset for Hindi to English conversion of text.
A. RNN
 A recurrent neural network (RNN) is a class of artificial neural network where connections between nodes form a directed graph along a sequence. This allows it to exhibit temporal dynamic behavior for a time sequence. Unlike feedforward neural networks, RNNs can use their internal state (memory) to process sequences of inputs. This makes them applicable to tasks such as unsegmented, connected handwriting recognition or speech recognition.

B. LSTM
Long short-term memory (LSTM) networks were discovered by Hochreiter and Schmidhuber in 1997 and set accuracy records in multiple applications domains.
LSTM have revolutionize speech recognition, outperforming traditional models in certain speech applications. In 2009, a Connectionist Temporal Classification (CTC)-trained LSTM network was the first RNN to win pattern recognition contests when it won several competitions in connected handwriting recognition.In 2014, the Chinese search giant Baidu used CTC-trained RNNs to break the Switchboard Hub5'00 speech recognition benchmark without using any traditional speech processing methods.LSTM also improved large-vocabulary speech recognition and text-to-speech synthesis and was used in Google Android.
LSTM broke records for improved machine translation, Language Modeling and Multilingual Language Processing. LSTM combined with convolutional neural networks (CNNs) improved automatic image captioning.

