# Real-Time-Speech-Emotion-Recognition

This project is a real-time speech emotion recognition system that detects emotions such as neutral, happy, sad, angry, fear, disgust, surprise, and calm from live audio using machine learning models trained on the RAVDESS and custom datasets. It features a GUI with real-time waveform visualization, logs predictions to a CSV, and provides instant feedback via text-to-speech. The system can be applied in human–computer interaction, customer service monitoring, mental health tracking, entertainment, and education to make interactions more responsive and emotion-aware

This Project is based on Automatic Speech Recognition (ASR)

## Automatic Speech Recognition (ASR) 
ASR technology is a key component for converting speech to text, making it a valuable tool in today’s digital world. Its applications are vast and diverse, spanning various industries. ASR can efficiently and accurately transcribe audio files into plain text. It also powers voice assistants, enabling seamless interaction between humans and machines through spoken language. It’s used in myriad ways, such as in call centers that automatically route calls and provide callers with self-service options.
By automating audio conversion to text, ASR significantly saves time and boosts productivity across multiple domains. Moreover, it opens up new avenues for data analysis and decision-making.
That said, ASR does have its fair share of challenges. For example, its accuracy is diminished when dealing with different accents, background noises, and speech variations — all of which require innovative solutions to ensure accurate and reliable transcription. The development of ASR systems capable of handling diverse audio sources, adapting to multiple languages, and maintaining exceptional accuracy is crucial for overcoming these obstacles.

For this task, I have used OpenAI's Whisper Model, which is a Speech Recognition Model

## Whisper: A Speech Recognition Model 
Whisper is a speech recognition model also developed by OpenAI. This powerful model excels at speech recognition and offers language identification and translation across multiple languages. It’s an open-source model available in five different sizes, four of which have an English-only variant that performs exceptionally well for single-language tasks.
Whisper utilizes a Seq2seq (i.e., transformer encoder-decoder) architecture, a common approach employed in language-based models. This architecture’s input consists of audio frames, typically 30-second segment pairs. The output is a sequence of the corresponding text. Its primary strength lies in transcribing audio into text, making it ideal for “audio-to-text” use cases.
## Real-Time Sentiment Analysis 
Next, let’s move into the different components of our real-time sentiment analysis app. We’ll explore a powerful pre-trained language model and an intuitive user interface framework.

## Hugging Face Pre-Trained Model 
I relied on the DistilBERT model in my previous article, but we’re now trying something new. To analyze sentiments precisely, we’ll use a pre-trained model called roberta-base-go_emotions, readily available on the Hugging Face Model Hub.

## Gradio UI Framework 
To make our application more user-friendly and interactive, I’ve chosen Gradio as the framework for building the interface. Last time, we used Streamlit, so it’s a little bit of a different process this time around. You can use any UI framework for this exercise.

I’m using Gradio specifically for its machine learning integrations to keep this tutorial focused more on real-time sentiment analysis than fussing with UI configurations. Gradio is explicitly designed for creating demos just like this, providing everything we need — including the language models, APIs, UI components, styles, deployment capabilities, and hosting — so that experiments can be created and shared quickly.

## Core Technologies Used:
* Python
* Deep Learning: PyTorch
* Dataset: Hugginface robertta-base-go_emotions
* NLP Framework: Huggingface.
