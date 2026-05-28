# PROGRAMMING-poe2026-

Project Description
This project is a **Cybersecurity Awareness Chatbot** in a console application. The chatbot interacts with users, introduces basic cybersecurity concepts, and answers common cybersecurity questions.

The goal of the chatbot is to educate users about online safety, including phishing, password protection, and malware awareness.



## Features

* Interactive console chatbot
* User greeting and name detection
* Typing animation for realistic responses
* ASCII styled interface
* Voice greeting using audio playback converted to wav
* Basic cybersecurity awareness responses
* Keyword detection for common questions



## Technologies Used

* C# .NET Console Application
* System.Media (for voice greeting)
* Threading (for typing animation)



## Cybersecurity Topics Covered

The chatbot provides basic information about:

* Phishing attacks
* Password safety
* Malware threats
* Safe internet practices
* Cybersecurity awareness



## How to Run the Project

1. Clone the repository
2. Open the project in Visual Studio
3. Build the solution
4. Run the program

The chatbot will start in the console and begin interacting with the user.



## Future Improvements

- Add improved AI based responses
- Expand cybersecurity knowledge base
- Add graphical interface
- Add more improved voice interaction

## About Part2 

CyberBot is a Windows desktop application developed using WPF (Windows Presentation Foundation) and C#. It is designed to help everyday users understand cybersecurity concepts such as phishing, passwords, malware, VPNs, scams, and privacy through a friendly chatbot interface.

## Features

### 1. Multi-Screen UI
- **Start Screen** — Welcome screen with logo
- **Name Screen** — Personalized greeting by asking the user's name
- **Greeting Screen** — Displays a welcome message before entering the chat
- **Chat Screen** — Main chat interface

### 2. Keyword Recognition
The chatbot recognizes cybersecurity-related keywords and responds with relevant tips:
- password — Password safety advice
- phishing — Phishing awareness tips
- vpn — VPN usage guidance
- malware / virus — Malware protection tips
- scam — Scam awareness advice
- privacy — Online privacy tips
- 2fa / two factor — Two-factor authentication info
- firewall — Firewall explanation
- ransomware — Ransomware awareness
- social engineering — Social engineering explanation

### 3. Random Responses
For each cybersecurity topic, the chatbot randomly selects from multiple predefined responses, keeping the conversation varied and engaging every time.

### 4. Conversation Flow
The chatbot maintains context across messages. Users can say:
- *"Tell me more"*
- *"Give me another tip"*
- *"Explain more"*
- *"Why?"*

The bot will continue on the last discussed topic without needing to restart.

### 5. Memory and Recall
- Remembers the user's **name** throughout the session
- Remembers the user's **favourite cybersecurity topic**
- Users can ask *"Do you remember me?"* and the bot will recall stored details
- Personalizes responses using the remembered name

### 6. Sentiment Detection
Detects the user's emotional state and responds accordingly:
- **Worried / Scared** → Provides reassurance and a helpful tip
- **Frustrated / Confused** → Offers encouragement and clarification
- **Curious / Interested** → Encourages learning and remembers their topic of interest
