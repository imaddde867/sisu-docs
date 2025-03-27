# Sisu-Speak

This project leverages AI and Natural Language Processing (NLP) to create an interactive Finnish language tutor. It analyzes spoken input from users, assesses pronunciation, grammar, and conversational context, and provides real-time feedback to help learners improve their Finnish skills.

## Overview

The system captures spoken audio, processes it using speech-to-text and pronunciation analysis, and evaluates it against Finnish language rules and conversational relevance. Feedback is generated and delivered as audio to the user, creating an immersive learning experience.

## Flowchart

Below is the process flow of the Finnish Language Tutor:

![Flowchart of Finnish Language Tutor](Documentation/Editor%20%7C%20Mermaid%20Chart-2025-03-27-151933.png)

### Process Description
1. **Audio Capture**: Records the user's spoken Finnish input.
2. **Audio Preprocessing**: Cleans and prepares the raw audio data.
3. **Speech-to-Text (STT)**: Converts audio into transcribed text.
4. **Pronunciation Analysis**: Assesses how accurately words are pronounced.
5. **Accent Recognition**: Identifies the user’s accent for tailored feedback.
6. **Expected Pronunciation Generation**: Creates a reference pronunciation based on the transcribed text.
7. **Assessment**: Evaluates:
   - Pronunciation accuracy (voice vs. expected).
   - Communication quality (clarity, effectiveness).
   - Grammar and Finnish language rules.
   - Conversational relevance.
8. **Feedback Generation**: Combines assessment results into actionable feedback.
9. **Text-to-Speech (TTS)**: Converts feedback into audio for the user.

## Purpose

This tool uses AI-driven NLP to provide personalized tutoring for Finnish learners, focusing on pronunciation, grammar, and practical communication skills. It’s ideal for language enthusiasts or students aiming to master Finnish in a conversational context.

## Usage

- Speak Finnish into the system.
- Receive immediate audio feedback on your pronunciation, grammar, and conversational fit.
- Iterate and improve based on the tutor’s guidance.
