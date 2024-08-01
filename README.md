# Medical-Visual-Question-Answering
 Developed a medical VQA system using BLIP (Bootstrapping Language-Image Pre-training) to assist in diagnosing pathology images by providing accurate, real-time answers to medical questions.
##Features
Visual Question Answering: Allows users to ask questions about medical images and receive accurate answers.
Image-Text Retrieval: Supports image-text matching for improved diagnostic support.
##Dataset
The PathVQA dataset is used for training and evaluation. This dataset includes question-answer pairs related to pathology images, with both open-ended and binary "yes/no" questions. The images and captions are sourced from publicly available pathology textbooks and digital libraries.
##Model Architecture
The BLIP model is utilized for this project, which is capable of performing various multi-modal tasks including VQA and image-text retrieval. The model effectively handles noisy web data by generating synthetic captions and filtering out noise.
