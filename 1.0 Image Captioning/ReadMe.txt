Suma is wonderful mentor cum friend. She helped me all ways in job finding. 

Majoriy she help me in resume biulding and networking. She also helped me to cover my 2 yr gap in my carrer. 
Apart from it she help me in cracking Managerial and HR interviews, how to face it , how to answer.

There were time when i got rejected at very last stage of interview, she boost my confidence so i sayrted again to give interviews.
Suma, I will always be grateful to you for your support and kindness.

Thanks


24/1/2020
InceptionV3
https://github.com/hlamba28/Automatic-Image-Captioning/blob/master/Automatic%20Image%20Captioning.ipynb

data processing
https://github.com/salkhan23/stat_946_project/blob/ae0c2d3043ae3cfa1f5f18a21e6a39fd44dde850/flickr_datasets.py
https://github.com/nitinkaushik01/Deep_and_Machine_Learning_Projects/blob/master/Image_Caption_Project/Image_caption_Project.ipynb

https://github.com/yashk2810/Image-Captioning/blob/master/Image%20Captioning%20InceptionV3.ipynb
https://towardsdatascience.com/step-by-step-vgg16-implementation-in-keras-for-beginners-a833c686ae6c

17/1/2020
https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8
https://github.com/yashk2810/Image-Captioning/blob/master/Image%20Captioning%20InceptionV3.ipynb

8/12/2019
https://ai.stackexchange.com/questions/10114/whats-the-commercial-usage-of-image-captioning
https://towardsdatascience.com/jupyterlab-you-should-try-this-data-science-ui-for-jupyter-right-now-a799f8914bb3
https://ai.googleblog.com/2014/11/a-picture-is-worth-thousand-coherent.html
https://ai.googleblog.com/2016/09/show-and-tell-image-captioning-open.html
http://dbs.cloudcv.org/captioning
https://www.freecodecamp.org/news/building-an-image-caption-generator-with-deep-learning-in-tensorflow-a142722e9b1f/


image captioning
https://medium.com/mlreview/multi-modal-methods-image-captioning-from-translation-to-attention-895b6444256e
https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/
https://medium.com/@raman.shinde15/image-captioning-with-flickr8k-dataset-bleu-4bcba0b52926
https://github.com/pxu4114/Image-captioning
https://www.kaggle.com/hsankesara/image-captioning

Code -- COCo
https://github.com/tensorflow/docs/blob/master/site/en/tutorials/text/image_captioning.ipynb

Download dataset from here
https://github.com/jeffheaton/t81_558_deep_learning/blob/master/t81_558_class_10_4_captioning.ipynb

-----------------------------------------------------
Capstone Project Ideas

1.	Image captioning

Image captioning involves the task of generating language descriptions of visual content, like image or videos.
Image captioning is to understand objects in images, relate to one another and translating it all into natural-sounding language.
Accurately describing a complex scene requires a deeper representation of what’s going on in the scene, capturing how the various objects relate to one another and translating it all into natural-sounding language.
Accurate image captioning is a challenging task that requires advancing the state of the art of both computer vision and natural language processing.

This kind of system could eventually help 
o	visually impaired people understand pictures, 
o	Provide alternate text for images in parts of the world where mobile connections are slow, and make it easier for everyone to search on Google for images.
o	Semantic image search
o	Bering visual intelligence to chat board
o	Help visually impaired people to see world around them
Reference for datasets:
http://cocodataset.org/#explore
https://www.flickr.com/photos/tags/dataset/
http://academictorrents.com/details/9dea07ba660a722ae1008c4c8afdd303b6f6e53b

2.	Toxicity classification by BERT
To understand toxic conversational attributes, in comments text form
Each comment in Train dataset has a toxicity label (target), and models should predict the target toxicity for the Test data. 
This attribute (and all others) are fractional values which represent the fraction of human raters who believed the attribute applied to the given comment. 
For evaluation, test set examples with target >= 0.5 will be considered to be in the positive class (toxic).
The data also has several additional toxicity subtype attributes. Models do not need to predict these attributes for the competition, they are included as an additional avenue for research. Subtype attributes are:
•	severe_toxicity , obscene, threat, insult, identity_attack, sexual_explicit
Reference for dataset:
https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data

3.	Speech recognition  
Voice-to-text is a type of speech recognition program that converts spoken to written language. 
This type of speech recognition software is extremely valuable to anyone who needs to generate a lot of written content without a lot of manual typing. 
It is also useful for people with disabilities, like the hearing impaired. That make it difficult for them to use a keyboard.

e.g Medical Speech, Transcription, and Intent
This data contains thousands of audio utterances for common medical symptoms like “knee pain” or “headache,” totaling more than 8 hours in aggregate. Each utterance was created by individual human contributors based on a given symptom. These audio snippets can be used to train conversational agents in the medical field.
This Figure Eight dataset was created via a multi-job workflow. The first involved contributors writing text phrases to describe symptoms given. For example, for “headache,” a contributor might write “I need help with my migraines.” Subsequent jobs captured audio utterances for accepted text strings.
Note that some of the labels are incorrect and some of the audio files have poor quality. I would recommend cleaning the dataset before training any machine learning models.
This dataset contains both the audio utterances and corresponding transcriptions.
Reference for dataset:
https://www.kaggle.com/paultimothymooney/medical-speech-transcription-and-intent
https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data



------------------------------------------------------
Domain Background:
Image captioning is the process by which names or description is automatically assigns to digital image. 
Objective is to capture objects contained in an image, and also express how these objects relate to each other as well as their attributes and the activities they are involved in
This kind of system could eventually help 
o	visually impaired people understand pictures, 
o	Provide alternate text for images in parts of the world where mobile connections are slow, and make it easier for everyone to search on Google for images.
o	Semantic image search
o	Bering visual intelligence to chat board
o	Help visually impaired people to see world around them
The web is filled with billions of images, helping to entertain and inform the world on a countless variety of subjects. However, much of that visual information is not accessible to those with visual impairments, or with slow internet speeds that prohibit the loading of images. 
Problem Statement:
Image captioning involves the task of generating natural language descriptions of visual content with the use of datasets comprising of image-caption pairs
Image captioning is to understand objects in images, relate to one another and translating it all into natural-sounding language.
Accurately describing a complex scene requires a deeper representation of what’s going on in the scene, capturing how the various objects relate to one another and translating it all into natural-sounding language.
Accurate image captioning is a challenging task that requires advancing the state of the art of both computer vision and natural language processing.

Dataset and input
1.	Conceptual Captions Dataset 
a.	It is a new dataset consisting of ~3.3M images annotated with captions. 
b.	Conceptual Caption images and their raw descriptions are harvested from the web, and therefore represent a wider variety of styles. 
c.	More precisely, the raw descriptions are harvested from the Alt-text HTML attribute associated with web images. 
d.	To arrive at the current version of the captions, we have developed an automatic pipeline that extracts, filters, and transforms candidate image/caption pairs, with the goal of achieving a balance of cleanliness, informativeness, fluency, and learnability of the resulting captions.
2.	MS-COCO – COCO is a large-scale object detection, segmentation, and captioning dataset. COCO has several features: 330K images (>200K labeled)Object segmentation
a.	330K images (>200K labeled)
b.	1.5 million object instances
c.	80 object categories
d.	91 stuff categories
e.	5 captions per image
3.	Flickr8K dataset 
a.	comprised of more than 8,000 photos and up to 5 captions for each photo.
b.	build models on your workstation using a CPU.
4.	Flickr30k
5.	SBU
6.	Adobe_MIT FiveK, contains random images from Intagram 

Solution Statements:
Automatically describing the content of an image is a fundamental problem in artificial intelligence that connects computer vision and natural language processing.

There are 2 leading approaches :
One stream takes end to end , encoder decoder framework adopted from machine translation.
Use CNN to extract high level images features and fed them into LSTM for caption generation. Thi went one step further by introducing attention mechanism. 

Second stream applies compositional framework, it divides captions generation into several parts: word detector by a CNN, caption candidates generation by a maximum entropy model and sentence re-ranking by deep multimodel semantic model.

The main component include
•	Vision model using deep residual network – deep residual network(ResNets)
•	Language and semantic ranking model 
o	Use of LSTM / GRU for caption generation
o	use MELM + DMSM, MELM(maximum entropy language model) together with a deep multimodel similarity model(DMSM) 
o	use MELM + GRNN 

•	An entities recognition model that identifies celebrities and landmarks
•	A classifier for estimating the confidence score for each output caption
•	

Evaluation Matrix

Metrics such as BLUE, METEOR and CIDEr are handy for fast development and tuning 
BLEU score [38], which is a form of precision of word n-grams between generated and reference sentences
BLEU score [38], which is a form of precision of word n-grams between generated and reference sentences

Reference:
https://ai.google.com/research/ConceptualCaptions

--------------
https://towardsdatascience.com/explaining-feature-importance-by-example-of-a-random-forest-d9166011959e
https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114
https://www.kaggle.com/nextbigwhat/eda-for-categorical-variables-a-beginner-s-way
https://towardsdatascience.com/exploratory-data-analysis-categorical-data-part-ii-5de835850f0f
