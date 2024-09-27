# GotU Assistant App

![License](https://img.shields.io/github/license/your-username/gotu-assistant-app)
![Python Version](https://img.shields.io/badge/python-3.12-blue)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

GotU Assistant is an AI-powered voice assistant designed to revolutionize the way students access information. By leveraging cutting-edge speech recognition and natural language processing technologies, GotU Assistant enables students to get quick and accurate answers without the need for typing. This project showcases innovative use of AI to enhance learning experiences, making it an excellent addition to any tech portfolio.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Motivation](#motivation)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Future Development](#future-development)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Hands-Free Interaction**: Voice-activated assistant that listens and responds to queries.
- **AI-Powered Responses**: Utilizes OpenAI's GPT technology for intelligent and context-aware answers.
- **Real-Time Speech Recognition**: Converts spoken words to text swiftly and accurately.
- **Text-to-Speech Conversion**: Provides natural-sounding verbal responses.
- **Customizable Functions**: Easily extendable to include new features and integrations.

## Demo

[![GotU Assistant Demo](https://img.youtube.com/vi/your-demo-video-id/0.jpg)](https://www.youtube.com/watch?v=your-demo-video-id)

*Click the image above to watch a demo of GotU Assistant in action.*

## Motivation

In today's fast-paced educational environment, students need quick and efficient ways to access information. Typing can be a bottleneck, especially when multitasking or on the go. GotU Assistant addresses this challenge by providing a seamless voice interface, allowing students to focus on learning rather than navigating through resources.

## Technologies Used

- **Programming Language**: Python 3.12
- **Frameworks and Libraries**:
  - [LiveKit Agents](https://github.com/livekit) is used to manage audio streams and real-time communication.
  - [OpenAI API](https://openai.com/) for advanced language understanding and generation.
  - [Silero VAD](https://github.com/snakers4/silero-vad) for Voice Activity Detection.
  - [Python Dotenv](https://pypi.org/project/python-dotenv/) for environment variable management.

## Installation

### Prerequisites

- Python 3.12+
- An OpenAI API key

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Kaydenletk/gotu-assistant-app.git
   cd gotu-assistant-app

2. **Set Up a Virtual Environment**

  ```bash
  python3 -m venv venv
  source venv/bin/activate

3. **Install Dependencies**
  ```bash
  pip install -r requirements.txt

4. **Configure Environment Variables**
  Create a .env file in the root directory and add your OpenAI API key:
  ```dotenv
OPENAI_API_KEY=your-api-key-here

##Usage
To start the GotU Assistant, run:

  ```bash

  python3 main.py start

##The assistant will greet you with:

"Hey, how can I help you today!"

You can then ask questions or request information verbally, and the assistant will provide immediate spoken responses.

##Example Interactions

**Academic Queries**

"What is the Pythagorean theorem?"
"Explain the concept of supply and demand."

**General Knowledge**

"Who wrote 'To Kill a Mockingbird'?"
"What is the capital of France?"

**Productivity Assistance**

"Set a reminder for my study session at 6 PM."
"Add 'Buy textbooks' to my to-do list."

##Future Development

We plan to enhance GotU Assistant with additional features:

Multilingual Support: Enable interactions in multiple languages.
Integration with Educational Platforms: Connect with services like Blackboard or Canvas.
Personalized Learning Paths: Provide customized study recommendations based on user interactions.
Offline Mode: Basic functionalities without the need for an internet connection.

##Contributing
We welcome contributions from the community!

1.**Fork the Repository**

2.**Create a Feature Branch**

  ```bash
  git checkout -b feature/your-feature
  Commit Your Changes

bash
Copy code
git commit -m 'Add your feature'
Push to the Branch

bash
Copy code
git push origin feature/your-feature
Open a Pull Request

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or inquiries:

Name: Your Name
Email: your.email@example.com
LinkedIn: Your LinkedIn Profile
GitHub: your-username
GotU Assistant App is continually evolving. Stay tuned for updates and feel free to reach out for collaboration opportunities!
