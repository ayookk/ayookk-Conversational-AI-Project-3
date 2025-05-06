📢 Conversational AI Project 3: Multimodal Audio Analysis with Google Cloud LLM
This project is a voice-based AI application designed to process and analyze user-recorded audio files using Google Cloud's multimodal large language model (LLM) APIs. It builds on Project II by simplifying the architecture — replacing multiple individual APIs with a single LLM endpoint that handles both transcription and sentiment analysis in one call.

🚀 Features
Audio Upload Interface
Record or upload audio questions through a clean web interface.

LLM-Based Transcription & Sentiment Analysis
Automatically transcribes audio and performs sentiment analysis via Google Cloud’s multimodal LLM in a single API call.

Persistent Interaction History
Saves all transcripts and sentiment analysis results to individual text files for future reference.

Simplified Architecture
Removed all legacy Text-to-Speech (TTS) functionality and consolidated analysis into a single streamlined LLM call.

Cloud Deployment
Fully deployed and hosted on Google Cloud Run, ensuring scalability and accessibility.

🛠 Tech Stack
Python + Flask — Web server and backend logic

Google Cloud LLM API — For transcription and sentiment in one call

JavaScript (MediaRecorder) — For browser-based audio recording

Google Cloud Run — Deployment platform

Google Cloud Storage — For saving audio and results

