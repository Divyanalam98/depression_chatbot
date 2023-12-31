# Adapt/Enhance ChatGPT for Live Line

![image](https://github.com/Divyanalam98/depression_chatbot/assets/63960112/6ca4ee34-5356-4685-b7db-6a7aa1c79506)


In today's high-stress environment, mental health issues are prevalent. However, with the advancements in AI and ML, businesses are developing virtual chatbots. 
These tools offer a confidential platform for users to discuss their concerns and receive guidance, making mental health support more accessible.
ChatGPT is a powerful language model that can generate human-like responses to user input after being trained on a large dataset of human conversation. 
As a result, ChatGPT is an excellent choice for developing a chatbot that can offer support and guidance to users seeking help with their mental health.

## Why OpenAI GPT?
Existing therapy chatbots are usually retrieval-based and need users to provide them with a limited set of choices, which may not be suitable for all use cases.
With the help of generative approaches such as the OpenAI GPT models, conversation bots related to therapy might become more dynamic than in the past. 
The term "pre-trained" refers to a factory model made public without any additional changes and is based on generic training data. 
A domain-specific dataset is used to fine-tune the model based on the pre-trained model with an application goal. 
The goal of this paper was to see how well these GPT pre-trained and tuned models perform as therapy chatbots. 

## Integrating Voice
Another unique feature to be mentioned is integrating a voice assistant with the GPT model. Combining the functionality of GPT and a voice assistant can be a revolutionary concept. 
AI-based virtual assistants will be actively used in the future as these assistants help provide users with a personalised experience. 
These AI assistants can be used across a broad range of use cases. 
Chatbots are more of a text-based customer service. Voice assistants provide service by utilizing speech recognition and analysis. 
Data privacy can be incorporated in voice assistants without storing any PII information. These assistants can incorporated in various sectors like banking, information technology and medicine.

## Benefits, Risks and Limitations
It is important to discuss about the benefits, risks and limitations of GPT model as chatbot for healthcare. Chatbots would help in understanding patients better, collecting symptoms or medical history, 
and help create a personalized service for the patients. 
Talking about the risks and limitations, heavy computational power required and storage issues can cause blockers. This might turn out to be an issue as not all healthcare providers would be willing to adapt. 
There are chances of biases to creep in based on the training data. 
Apart from these drawbacks, GPT looks like a solution for faster, accurate diagnoses and reduced healthcare costs as well.

## Setup

Step 1: 
Execute https://drive.google.com/file/d/1CplLPvIgFYcCiwlgMDaXYEcUkGAGtvBu/view?usp=drive_link. This code is attached to the GitHub repository as well. This code would help in creating a finetuned model. This model is trained on mental health related data https://drive.google.com/drive/folders/1DgiTL6nsRulV61aI1pGqvMyfPykJPhiT?usp=drive_link.

Step 2: [Optional] 
Post fine-tuning, encapsulate your code and its dependencies into a Docker image. https://docs.docker.com/reference/

Step 3: 
Execute https://colab.research.google.com/drive/12IqVDuPBDvZesNEDlgDTHri0Je3NrO73?usp=sharing to get your interface (GUI).

Step 4: [Optional] 
Run 'gradio deploy' to permanently deploy on Hugging Face - Spaces. You will have to create requirements.txt for all dependencies here.

## Additional Notes:

We worked on building a depression chatbot using LSTM, BERT and GRU. You can find all the related codes and documentation here. 
https://drive.google.com/drive/folders/1MQSkDMDDLfG6k1QJ5rZvI1wfu0XP8C2w?usp=drive_link

