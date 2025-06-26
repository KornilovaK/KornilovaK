# About me 

|           |                       Hard skills|
|----------:|----------------------------------|
|Programming|                       Python, C++|
|   Software|   SQL, Git, Docker, Triton, Linux|
|         ML|DL, ML, Analytics, CV, NLP, Agents|


## EDUCATION
National University of Science and Technology MISIS, Applied Math, Bachelor

## EXPIRIENCE
### Data Scientist at Sber Rist Modeling & Research, RnD
March 2024 - June 2025
> I worked on Agents, RAG, LLMs, papers <3

### ML Teacher for students from specialized Moscow Math schools
September - December 2024
> I conducted lectures and seminars in various areas of ML, and at the end of the course they will have to prepare and defend
projects.


## COURCES
* Giraffe-ai MIPT: Classical and deep ml
* NLP course for you: NLP
* Deep Learning School: Deep learning, CV/NLP

## ACHIEVEMENTS
* One of 20 participants of T-Bank — Sirius University educational program. Theme: Modern machine learning technologies and their applications. Direction: NLP. Sochi, Russia, December 2024
* Winner of hackathon PowerSafe. AI for automatic monitoring of security zones of power lines. Innopolis, Russia, November 2024
* Winner of the AI hackathon at MIPT (Olympiad ”I am a PROFESSIONAL”). Case: A multimodal model of the propensity to buy products. Moscow, Russia, July 2024
* Winner of IT case championship ”CUP IT”, award: ”High Quality Awards”. Section: ”Data Analytics”. Moscow, Russia, April 2024

## PROJECTS
### [LLM data labeling](https://github.com/Dimmension/tbank-ml-camp-sirius.git)
<details>
<summary>December 2024</summary>
We developed an LLM-based RAG system to fix annotators' errors. There are a fusion of FAISS retrieval and BM25 and an ensemble on 3 LLMs: Llama 3.1, Qwen 2.5, Gemma 2
</details>

### [Telegram bot for generating contextual stickers](https://github.com/firegory/StickerIt.git)
<details>
<summary>December 2024</summary>
The latest messages when calling the bot are sent to the input of the LM (Qwen 2.5 with SFT). It generates a coherent prompt, which is fed to the input of the diffusion image model (Kaspersky), at the output of which we get our sticker
</details>

### [Reflex Attention](https://github.com/KornilovaK/reflex_attention.git)
<details>
<summary>November 2024</summary>
I implemented the modified attention blocks in the gpt architecture and conducted experiments by training several models
with different implementations and parameters.
</details>

### [Telegram bot ”QAcumber” for question-answering task](https://github.com/KornilovaK/tg-bot-russian-qa.git)
<details>
<summary>September 2024</summary>
I’ve collected datasets, fine tuned Distillbert and T5 with Lora for QA task in Russian, integrated trained model to tg
bot and wrapped an app in a Docker container. F1: 0.72, SAS: 0.81.
</details>

### [Multimodal model for the task of matching goods’ cards from the Ozon](https://github.com/KornilovaK/Multimodal-model.git)
<details>
<summary>June 2024</summary>
Product cards are a set of images, text descriptions, and tabular characteristics. I preprocessed data, encoded it to the
embeddings, created custom NN architecture and trained to the binary classification task. PR-AUC: 0.87.
</details>

### [Telegram bot for photo styling](https://github.com/KornilovaK/tg-style-bot.git)
<details>
<summary>February 2024</summary>
The bot can transfer the style from one photo to another: you need to send two photos and receive a photo with the
transferred style in response using CycleGAN. It is possible to transfer the style using GANs by selecting one of the 4
suggested styles and sending 1 photo. Integrated onnx models to tg bot and wrapped an app in a Docker container.
</details>

### [Mobile app ”Sign language translator” for Russian gesture language](https://github.com/KornilovaK/Sign-Language-Translator-app.git)
<details>
<summary>May 2023</summary>
The Sign Language Interpreter mobile app, made in Android studio. It is intended for communication between deaf
people and speakers who don’t know Russian sign language. The app translates gestures from the camera in real time
and outputs the corresponding words. Uses CNN and RNN for time sequences.
</details>
