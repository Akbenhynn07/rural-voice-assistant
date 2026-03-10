# Rural Voice Assistant

A multilingual AI-powered voice assistant that allows rural users to book local transport using natural speech.

The system integrates speech recognition, large language models, voice synthesis, and cloud databases to simulate a real-world ride booking interaction.

---

## Motivation

In many rural areas, booking transport often requires phone calls, physical visits, or assistance from others.

Voice-based AI systems can remove these barriers by enabling users to simply speak their request.

This project explores how voice AI can make public transport services more accessible through natural language interaction.

---

## Features

* Wake word activation
* Multilingual speech recognition (English, Hindi, Telugu, Tamil)
* AI-powered conversation using Azure OpenAI
* Ride booking simulation with OTP generation
* Voice response using neural speech synthesis
* Conversation memory stored in CosmosDB
* Web interface for microphone interaction

---

## System Architecture

```
User Speech
   ↓
Azure Speech Recognition
   ↓
Automatic Language Detection
   ↓
Azure OpenAI (Intent Understanding)
   ↓
Ride Booking Logic
   ↓
Azure Speech Synthesis
   ↓
Voice Response to User
```

---

## Example Interaction

**User:**
Agent book auto to railway station

**Assistant:**
The ride distance is 8 km and the fare is 170 rupees. Would you like to confirm?

**User:**
Yes

**Assistant:**
Confirmed! Your ride is on the way. The driver name is Ramesh and the vehicle number is TS08FI8976. Your OTP is 4832.

---

## Tech Stack

* Python
* Flask
* Azure Speech Services
* Azure OpenAI
* Azure CosmosDB
* HTML / JavaScript

---

## Project Structure

```
rural-voice-assistant
│
├── app.py
├── requirements.txt
├── .env.example
│
├── templates
│   └── index.html
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## How to Run

Clone the repository:

```
git clone https://github.com/Akbenhynn07/rural-voice-assistant.git
```

Install dependencies:

```
pip install -r requirements.txt
```

Create a `.env` file based on `.env.example`.

Run the server:

```
python app.py
```

Open in browser:

```
http://localhost:5000
```

---

## Future Improvements

* Integration with real transport booking systems
* Offline speech recognition models
* Mobile and embedded device deployment
* Custom speech models for regional accents

---

## Author

Akshay Benhynn Yendloori
BTech Student – Malla Reddy University Hyderabad

AI Systems Builder | Speech AI | Machine Learning

Goal: Research in applied AI systems and intelligent infrastructure.
