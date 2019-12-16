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


------------------------------------------------------
Domain Background:
Image captioning is the process by which names or description is automatically assigns to digital image. 
Objective is to capture objects contained in an image, and also express how these objects relate to each other as well as their attributes and the activities they are involved in
This kind of system could eventually help visually impaired people understand pictures, provide alternate text for images in parts of the world where mobile connections are slow, and make it easier for everyone to search on Google for images.
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

Solution Statements:

Benchmark Model:
xx
Evaluation Matrix
Xx
BLEU score [38], which is a form of precision of word n-grams between generated and reference sentences
BLEU score [38], which is a form of precision of word n-grams between generated and reference sentences

This method can be regarded as a type of multi-class image classification with a very large number of classes - as large as the vocabulary size. Typically, image analysis in the form of extracted feature vectors and the training annotation words are used by machine learning techniques to attempt to automatically apply annotations to new images. The first methods learned the correlations between image features and training annotations, then techniques were developed using machine translation to try to translate the textual vocabulary with the 'visual vocabulary', or clustered regions known as blobs. Work following these efforts have included classification approaches, relevance models and so on.
The advantages of automatic image annotation versus content-based image retrieval (CBIR) are that queries can be more naturally specified by the user.[1] CBIR generally (at present) requires users to search by image concepts such as color and texture, or finding example queries. Certain image features in example images may override the concept that the user is really focusing on. The traditional methods of image retrieval such as those used by libraries have relied on manually annotated images, which is expensive and time-consuming, especially given the large and constantly growing image databases in existence.
Some annotation engines are online, including the ALIPR.com real-time tagging engine developed by Pennsylvania State University researchers, and Behold. Companies such as Canotic.com, Playment, Edgecase.ai, Microsoft VOTT.ai and dataloop.ai have all built automatic engines for video annotation. Additional companies such as Alegion.com, Infolks, DataPure.co, Scaleapi.com, Diffgram.com, Figure-eight.com offer a mix of automatic image annotation with a mix of manual overview when automation fails.

we’ve developed a machine-learning system that can automatically produce captions (like the three above) to accurately describe images the first time it sees them. This kind of system could eventually help visually impaired people understand pictures, provide alternate text for images in parts of the world where mobile connections are slow, and make it easier for everyone to search on Google for images.

B EING able to automatically describe the content of an image using properly formed English sentences is a very challenging task, but it could have great impact, for instance by helping visually impaired people better understand the content of images on the web. This task is significantly harder, for example, than the well-studied image classification or object recognition tasks, which have been a main focus in the computer vision community [1]. Indeed, a description must capture not only the objects contained in an image, but it also must express how these objects relate to each other as well as their attributes and the activities they are involved in. Moreover, the above semantic knowledge has to be expressed in a natural language like English, which means that a language model is needed in addition to visual understanding. Most previous at
•	Provision of captions to reduce the number of user operations (keying and selection) required to post a movie or image to improve posting volume of sticky media and therefore improve the position of a web site or page in terms of human interest
•	Provision of captions to provide HTML header and alt attribute content to improve search engine scoring of page for search terms related to the content of the movie or image
•	Testing to see if the content of an image submitted for posting matches the criteria intended by the owner or stake holder for the posting space on the basis of caption rather than directly through CNN categorization

Problem Statement:
Dataset and input
Solution Statements:
Benchmark Model:
Evaluation Matrix
Reference:
https://ai.google.com/research/ConceptualCaptions
