# FOTS
_-A Complete End-to-End Deep Learning implementation of FOTS - Fast Oriented Text Spotting with an unified network, which detects and recognizes text in an incidental scene._



---


# **Business Problem**
Text detection & recognition ( also called as text spotting) in an incidental images is considered as one of the most challenging tasks in computer vision (CV). It is an important task in many areas/domains like document analysis, autonomous cars, scene understanding, robot navigations, etc. Text in the natural images varies in font styles, sizes, strokes, alignment. Hence text spotting is one of the challenging tasks in computer vision domain.
Text spotting involves "localization" & "recognition" of text in the given image. Task at hand is a combination of Computer Vision (CV) + Natural Language Processing (NLP).



---


# **Use of Deep Learning to solve the problem**
Text spotting task involves text detection & text recognition. 
i) Text detection - Model need to detect & localize the text in the input image with bounding boxes around the text.
ii) Text recognition -Text regions that are detected in detection phase are extracted and used to predict the text characters. 
Traditionally, scene text spotting is to divide it into text detection and text recognition, which are handled as two separate tasks. But in this work, we are building  an end-to-end trainable fast oriented text spotting system with an unified network,  which can detect & recognize text simultaneously.



---



# **Dataset Overview**
There are many good datasets publicly available for natural scene text spotting. In this work, we'll use the same datasets that are used in the FOTS research paper i.e. Synth-Text & ICDAR-2015 datasets.



---
