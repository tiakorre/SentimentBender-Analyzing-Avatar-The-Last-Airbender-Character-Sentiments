# SentimentBender - Emotional Dynamics Analysis of Avatar The Last Airbender

## Background
"Avatar: The Last Airbender" is an animated television series renowned for its rich storytelling, complex characters, and emotional depth. As a dedicated fan of the series, I'm intrigued by its intricate emotional narratives and aim to explore them through data science techniques. This project seeks to quantitatively analyze the dialogue of "Avatar: The Last Airbender" characters to uncover the emotional and sentiment dynamics embedded within the series.

## Problem Statement
While the emotional depth of "Avatar: The Last Airbender" has been traditionally analyzed qualitatively, this project aims to apply natural language processing (NLP) techniques to quantitatively assess the emotional landscapes of its characters. By doing so, we seek to gain insights into how emotions contribute to storytelling and character development within the series.

## Objective
The primary objective of this project is to utilize NLP techniques to analyze the dialogues from "Avatar: The Last Airbender" and discern the most common emotions and sentiments conveyed by the main characters throughout the series. Specifically, we aim to:
1. Uncover patterns in character development and emotional expression.
2. Investigate how emotions evolve in response to central themes and plot developments.
3. Provide a quantitative analysis to complement existing qualitative analyses of the series.

## Dataset Description
The dataset comprises textual data extracted from the complete transcript of "Avatar: The Last Airbender," containing 13,369 lines of script across various episodes. Each entry includes the character's name, the respective episode, and the full script, facilitating a multifaceted analysis of emotional dynamics.

## Methodological Decisions and Biases
- Data Cleaning: Removing stage directions to prevent leakage of authorial intentions into the model.
- Selection of Characters: Focusing on the top 10 most frequently speaking characters to manage computational resources effectively.
- Exclusion of Narrator: Refining the dataset to exclude the narrator's dialogue.
- Model Selection: Utilizing the "michellejieli/emotion_text_classifier" model for emotion classification.
- Character Sample Size: Choosing the top 10 characters despite a larger character pool to reduce bias.

## Key Findings
The analysis revealed significant insights into the emotional landscapes of "Avatar: The Last Airbender" characters. Through sentiment and subjectivity analysis, as well as emotion classification modeling, patterns in character emotions were uncovered, providing a deeper understanding of the series' emotional dynamics.

## Future Work
Future enhancements may include subjectivity analysis, exploration of frequent bigrams, and trends in sentiment and subjectivity across episodes to further enrich our understanding of emotional evolution in the series.

## Tools and Libraries
- Pandas, NumPy: Data manipulation and analysis.
- Matplotlib, Seaborn: Data visualization.
- NLTK, TextBlob: Natural language processing tasks.
- WordCloud, Transformers: Additional NLP tasks and visualizations.
