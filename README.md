# Venom - Voice Assistant

Venom is a Python-based voice assistant that can execute various commands like playing YouTube videos, fetching the current time, searching Google, providing weather updates, and more. It uses **speech recognition** to process user commands and responds accordingly.

## Features
- **Play YouTube videos** using voice commands.
- **Fetch the current time** and announce it.
- **Get weather updates** for Chennai.
- **Search Wikipedia** for quick information.
- **Google search** directly from voice input.
- **Tell jokes** using the `pyjokes` module.
- **Respond to casual questions** like "Are you single?" or "Where are you?".
- **Voice-based interaction** with text-to-speech responses.

## Prerequisites
Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/sriman1229/venom-voice-assistant.git
   cd venom-voice-assistant
   ```

2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Set up your OpenWeather API key:
   - Sign up at [OpenWeather](https://openweathermap.org/) and get your API key.
   - Set an environment variable for security:
     ```sh
     export OPENWEATHER_API_KEY='your_api_key_here'
     ```
     (For Windows, use `set OPENWEATHER_API_KEY=your_api_key_here` in Command Prompt.)

## Usage
Run the assistant with:
```sh
python venom.py
```

Speak commands like:
- "Venom, play Shape of You"
- "Venom, what time is it?"
- "Venom, what's the weather?"
- "Venom, who is Elon Musk?"
- "Venom, tell me a joke."

## Technologies Used
- `speech_recognition` for processing voice commands
- `pyttsx3` for text-to-speech conversion
- `pywhatkit` for YouTube and Google search
- `wikipedia` for fetching summaries
- `requests` for API calls (weather data)
- `pyjokes` for generating jokes

## Future Enhancements
- Add support for multiple cities in weather updates.
- Implement a GUI using Tkinter or PyQt.
- Improve voice recognition accuracy with offline models.
- Enable continuous background listening with wake-word detection.

## License
This project is licensed under the MIT License. Feel free to use and modify it.

## Author
Developed by Sriman , Prasanna

