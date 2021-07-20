# multimodal-sentiment-analysis
Abstract

The Context GRU (cGRU) for each modality aimsto capture the context of the conversation by jointly encoding the utterance representation of that modal-ity (at timestamp in the given diagram) (and the previous times-tamp speaker state GRU output of that modality.This accounts for inter-speaker and intra-utterance dependencies to produce an effective context.

Introduction:

Multimodal sentiment analysis is a prominent field at the convergence of natural language processing, computer vision, and speech processing. The sensor can be indicated by spoken words, the emotional tone of the delivery and the accompanying face. For this reason, it is helpful to integrate visual, linguistic, and auditory approaches to sentiment prediction. Multimodal sentiment analysis integrates verbal and nonverbal behavior to predict user sentiment analysis is the process of finding positive or negative emotions in a text. It is often used by businesses to gain experience in social media, to measure a brand name, and to understand customers


CMU-MOSI Dataset:

Multimodal Corpus of Sentiment Intensity and Subjectivity Analysis (CMU-MOSI) dataset has been used in the paper. It is a collection of online videos where the speaker expresses his views about the movie. Each video is divided into multiple clips, and each a clip contains one idea expressed by one or more sentences. A clip contains one continuous y [−3, +3] sensor label the value representing the speaker's feelings in relation to a particular aspect of the movie. Figure 2 shows an image from the CMU-MOSI database. The CMU-MOSI database contains 93/2199 label videos and training is done on labeled videos. Each video in a file the CMU-MOSI database comes from a different speaker. We use a train and test sets described in [36] train in 52 videos / 1284 clips (52 different speakers), works on 10 videos / 229 clips (10 different speakers) and 31 video clips / 686 clips (31 different speakers). No speaker-based pollution in our testing of it our model is realistic and learns independent speaking features.

Methodology:


The Context GRU (cGRU) for each modality aimsto capture the context of the conversation by jointly encoding the utterance representation of that modal-ity (at timestamp in the given diagram) (and the previous times-tamp speaker state GRU output of that modality.This accounts for inter-speaker and intra-utterance dependencies to produce an effective context


![image](https://user-images.githubusercontent.com/51492488/126368164-733d9430-076a-4b9f-a4f5-eba28fde3a72.png)


CONCLUSION:



Sentiment analysis, also known as opinion mining, is essential for various reasons. It is specifically important for knowing the reviews of customers of different context where people use different methods to communicate their ideas. Due to the omnipresence of data and information and ease of access to the web, several platforms give people the opportunity to express themselves. A lot of work has been done with singular modality sentiment analysis like text or images. Fusing the different modes give better accuracy and robustness in detecting emotion and consequently sentiment analysis.

