# Food Recipe Generator App
# Overview
The Food Recipe Generator App is an innovative application that generates food recipes based on input video files from YouTube. By analyzing the content of cooking videos, the app extracts relevant information and presents users with detailed recipes.

# Features
Video Input: Users can input YouTube video links.
Audio Extraction: The app extracts audio from the video files.
Automatic Speech Recognition (ASR): Converts audio to text using the Whisper model.
Recipe Generation: Uses GPT-3, a large language model, to generate food recipes from the transcript.
Recipe Details: Extracts ingredients and required steps from the generated content.

# Models Used
Automatic Speech Recognition (ASR): Whisper - A model for converting speech to text.
Large Language Model (LLM): GPT-3 - Used to generate food recipes from video transcripts.

# Project Flow
Video Input: Users provide a YouTube video link.
Audio Extraction: The app extracts the audio from the video file.
Transcript Generation: Converts audio to text using the Whisper model.
Prompt Processing: Processes the transcript to generate food recipes using GPT-3.
Recipe Output: Outputs the ingredients and required steps for the recipe.

NOTE: The following project code will only work with english language and it is preffered to use python version 3.9

Special thanks to AI Anytime for their guidance and for the development of this project.
