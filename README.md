#  AI-Driven Business Meeting Summarizer
Automatically transcribe, extract, and summarize your meetings using state-of-the-art AI.
#  Overview
In today’s fast-paced business environment, meetings are frequent and information-heavy. This AI-powered tool streamlines the process of capturing, organizing, and summarizing key discussion points, decisions, and action items — all with minimal human effort.
#Features
 Speech-to-Text with Speaker Diarization using OpenAI Whisper

 Extractive Summarization using TextRank to select the most relevant dialogue

 Abstractive Summarization using a fine-tuned T5 Transformer for human-like summaries

 Searchable, Shareable Summaries for quick reference and follow-up

 Modular Design – Easily adaptable to other languages or business domains

# Tech Stack
Python

OpenAI Whisper

NLTK / SpaCy (for TextRank)

HuggingFace Transformers (T5 Model)

Flask (for API Integration, optional)

# Workflow
1. Upload a meeting audio file

2. Whisper transcribes and labels speakers

3. TextRank filters out non-essential dialogue

4. T5 reformulates extracted content into a coherent summary

5. Output: Clear, concise, and searchable meeting minutes

# Benefits
Saves time and effort in note-taking

Improves documentation consistency

Accelerates team alignment and follow-ups

Enhances knowledge retention across projects

# Use Cases
Team meetings

Client calls

Project stand-ups

Corporate training sessions 

# Installation
Installation 

git clone https://github.com/yourusername/business-meeting-summarizer.git  
cd business-meeting-summarizer  
pip install -r requirements.txt  

