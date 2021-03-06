# Automated-Question-Generation-and-Answer-Verification-using-Visual-Data

This paper delineates the automation of question generation as an extension to existing Visual Question Answering (VQA) systems. Through our research, we have been able to build a system that can generate questions and answer pairs on images. It consists of two separate modules—Visual Question Generation (VQG) which generates questions based on the image, and a Visual Question Answering (VQA) module that produces a befitting answer that the VQG module generates. Through our approach, we not only generate questions but evaluate the questions generated by using a question answering system. Moreover, with our methodology, we can generate question-answer pairs as well as improve the performance of VQA models. It eliminates the need for human intervention in dataset annotation and also finds applications in the field of the educational sector, where the requirement of human input for textual questions has been essential till now. Using our system, we aim to provide an interactive interface which helps the learning process among young children.

# Implementation Details

- MS COCO dataset,  VQA annotations and questions for train and test images.
- VGG19 model for image feature extraction.
- Tensorflow as a deep learning framework.
- NumPy for scientific computing with python.
- OpenCV for image processing.
- Natural Language Toolkit (NLTK) for language processing.
- Pandas for data manipulation.
- tqdm to check progress of training.
- Python 2.7

