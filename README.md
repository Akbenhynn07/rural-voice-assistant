# Rural Voice Assistant

A multilingual AI-powered voice assistant that allows rural users to book local transport using natural speech.

The system integrates speech recognition, large language models, voice synthesis, and cloud databases to simulate a real-world ride booking interaction.

## Features

• Wake word activation  
• Multilingual speech recognition (English, Hindi, Telugu, Tamil)  
• AI-powered conversation using Azure OpenAI  
• Ride booking simulation with OTP generation  
• Voice response using neural speech synthesis  
• Conversation memory stored in CosmosDB  

## Tech Stack

Python  
Flask  
Azure Speech Services  
Azure OpenAI  
Azure CosmosDB  
HTML / JavaScript  

## Architecture

User Voice  
↓  
Speech Recognition  
↓  
Language Detection  
↓  
AI Intent Understanding  
↓  
Ride Booking Logic  
↓  
Voice Response  

## How to Run

1. Clone the repository

2. Install dependencies

pip install -r requirements.txt

3. Create .env file using .env.example

4. Run the server

python app.py

5. Open browser

http://localhost:5000

## Future Improvements

• Real auto / cab integration  
• Offline speech models  
• Mobile deployment  
• Custom trained speech models
