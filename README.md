# YouTubeTranscriptSummarizer

**A Python tool for extracting and summarizing YouTube video transcripts.**

## Overview

YouTubeTranscriptSummarizer is a Python-based tool designed to extract and summarize transcripts from YouTube video URLs. This project simplifies the process of understanding long-form video content by generating concise summaries of the video's spoken content.

## Features

* **Automatic Transcript Extraction:** Fetches video transcripts using the `youtube_transcript_api` library.
* **Natural Language Processing (NLP):** Utilizes spaCy for text processing and analysis, including tokenization, part-of-speech tagging, and named entity recognition.
* **Text Summarization:** Implements frequency-based summarization techniques to extract the most important sentences and create a concise summary.
* **Customizable Input:** Works with any YouTube video URL that supports captioning.
* **User-Friendly Interface:** Provides a simple and intuitive command-line interface for easy use.

## Installation

1. **Install required dependencies:**
   ```bash
   pip install youtube-transcript-api spacy
