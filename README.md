# 🖼️PicTales
📌 Overview

The Image-to-Story Converter is a Streamlit-based web application that transforms uploaded images into short stories. It leverages deep learning models from Hugging Face for image captioning, text generation, and text-to-speech synthesis to create an interactive storytelling experience.

🚀 Features

Image Captioning: Generates a textual description of an uploaded image using BLIP (Salesforce/blip-image-captioning-base).

Story Generation: Converts the image description into a short, engaging story using GPT-Neo (EleutherAI/gpt-neo-2.7B).

Text-to-Speech (TTS): Converts the generated story into audio using ESPNet's Kan-Bayashi VITS model.

Interactive UI: Built with Streamlit for seamless user interaction.

🛠️ Tech Stack

Frontend: Streamlit (Python-based UI framework)

Backend: Hugging Face Transformers API

Deep Learning Models:

BLIP: Image captioning

GPT-Neo: Story generation

VITS: Text-to-speech

📌 Setup Instructions

1️⃣ Clone the Repository

  git clone https://github.com/yourusername/image-to-story-converter.git
  cd image-to-story-converter

2️⃣ Install Dependencies

Ensure you have Python 3.8+ installed, then run:

  pip install -r requirements.txt

3️⃣ Set Up Hugging Face API Token

Create a .env file in the project root and add your Hugging Face API token:

HUGGINGFACE_API_TOKEN=your_token_here

4️⃣ Run the Application

  streamlit run app.py

📸 Usage

Upload an image (JPG format).

Wait for the AI to generate an image description.

Receive a short story based on the image.

Listen to the generated story with text-to-speech functionality.

📌 Future Enhancements

Add support for more image formats (PNG, JPEG, etc.).

Implement multilingual text-to-speech options.

Enhance text generation with fine-tuned models.

