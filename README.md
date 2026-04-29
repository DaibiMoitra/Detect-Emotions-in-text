Building Multi-Task NLP model with LSTM : Detect Emotions, Hate Speech in text.
This project focuses on building a Multi-Task Natural Language Processing (NLP) model using LSTM (Long Short-Term Memory) networks to simultaneously perform Emotion Detection and Hate Speech Classification on textual data. Instead of training separate models for each task, a shared architecture is designed to learn common linguistic patterns, improving efficiency and generalization.

The model processes input text through embedding layers followed by LSTM networks to capture contextual and sequential dependencies. It then branches into task-specific output layers: one for identifying emotions (such as happiness, anger, sadness, etc.) and another for detecting whether the text contains hate speech.

This multi-task learning approach helps leverage shared representations between related tasks, leading to better performance, reduced training time, and improved scalability for real-world NLP applications like social media monitoring, content moderation, and sentiment analysis systems. This is the link to the project file-C:\Users\DELL\Downloads\Detect_Emotions_in_text (1).ipynb
