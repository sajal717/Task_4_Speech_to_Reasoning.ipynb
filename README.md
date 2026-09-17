# Task 4: Speech-to-Reasoning Pipeline

## Overview

This project implements a complete Speech-to-Reasoning pipeline using OpenAI Whisper and a 4-bit quantized Qwen language model.

## Pipeline

Audio Input
→ Whisper Speech Recognition
→ Transcribed Text
→ Qwen 2.5 3B Instruct (4-bit Quantized)
→ Reasoning / Question Answering

## Technologies Used

- Google Colab
- Python
- OpenAI Whisper
- Hugging Face Transformers
- Qwen 2.5 3B Instruct
- 4-bit Quantization
- PyTorch
- BitsAndBytes

## Features

- Converts spoken audio into text using Whisper
- Passes the transcription to a quantized language model
- Generates logical reasoning and question-answering responses
- Supports batch processing
- Demonstrates GPU memory usage
- Complete end-to-end speech-to-reasoning pipeline

## Sample Input

An audio question is provided to the Whisper ASR model.

## Output

The transcribed question is passed to the quantized Qwen model, which generates the final reasoning-based answer.

## Notebook

The complete implementation is available in `Task4.ipynb`.
