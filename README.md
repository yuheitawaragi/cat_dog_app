# 🐶🐱 Dog & Cat Breed Classification Web App
This repository contains a web application that classifies dog and cat breeds from uploaded images using a deep learning model, and generates a short Japanese description of the predicted breed using a Large Language Model (LLM).<br>
The application is built with Flask, PyTorch, and EfficientNet, and integrates an LLM via Ollama (Qwen2.5) for natural language generation.

## Features
- Upload an image of a dog or cat
- Predict the breed using a trained EfficientNet-B0 model
- Generate a beginner-friendly Japanese description (≤100 characters) using an LLM
- Simple and lightweight Flask-based web interface

## Model Overview
### Image Classification

