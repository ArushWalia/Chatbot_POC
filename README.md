# Chatbot_POC

A chatbot created using BERT By HuggingFace Liberary. 
The model used is bert-large-uncased-whole-word-masking-finetuned-squad which have: 
- 24 encoder layer
- 1024 hidden layer
- 16 Attention Head 
- 340 Million Parameters.
The model is fine-tuned on SQUAD dataset
The data set used is CoQA(conversation question answering dataset)
It contains 127,000+ questions with answers collected from 8000+ conversations![image](https://user-images.githubusercontent.com/98385899/173016886-9396f149-3762-40f0-b717-8762bb8d205e.png)
The model will use the PDF samples as knowledge base to retrive the answers for the questions asked.
