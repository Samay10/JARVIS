# JARVIS - Personal AI Assistant

A Python-based AI assistant inspired by Iron Man's JARVIS, featuring voice commands, automation capabilities, and a modern GUI interface.

## Features

### Voice Interaction
- Natural language voice commands
- Text-to-speech responses
- Multiple voice recognition languages (English and Hindi)
- Custom wake word ("Jarvis")

### Core Functionalities
- **Web Automation**
  - YouTube control (play, pause, skip, volume)
  - Chrome tab management
  - Website launches
  - Google search
  - Wikipedia searches

- **System Control**
  - Application launching (Chrome, VS Code, WhatsApp, Telegram)
  - Screenshot capture
  - File operations
  - System monitoring

- **Communication**
  - WhatsApp messaging
  - Email sending
  - Language translation

- **Entertainment**
  - Music playback
  - YouTube video playback
  - YouTube video downloading
  - Jokes
  - Book reading (PDF)

- **Utilities**
  - Weather updates
  - Dictionary lookup
  - Time and date
  - Reminders
  - Internet speed testing
  - Alarm setting

### Modern GUI
- Real-time animations
- System status display
- Time and date widgets
- Quick launch buttons
- Sleek dark theme interface

## Requirements

```python
# Core dependencies
pyttsx3
speech_recognition
beautifulsoup4
wikipedia
googletrans
PyAutoGUI
requests
pytube
PyPDF2
playsound
pyjokes
PyDictionary
speedtest-cli

# GUI dependencies
PyQt5
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/jarvis.git
cd jarvis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Update email and WhatsApp credentials in `main.py`:
```python
# Email configuration
server.login('your-email@gmail.com', 'your-password')

# WhatsApp numbers
# Update phone numbers in the Whatsapp() function
```

## Usage

1. Launch the GUI:
```bash
python JarvisGui.py
```

2. Click the "START" button to activate JARVIS

3. Use voice commands starting with "Jarvis" followed by your request:
- "Jarvis, open Chrome"
- "Jarvis, what's the temperature?"
- "Jarvis, send a WhatsApp message"
- "Jarvis, play music"

## Voice Commands

Here are some example commands:
- "Open {application}" - Launch installed applications
- "Play music" - Start music playback
- "Send WhatsApp message" - Initiate WhatsApp messaging
- "Take screenshot" - Capture screen
- "Tell me a joke" - Get a random joke
- "What's the temperature?" - Check weather
- "Search on Google" - Perform web search
- "Read a book" - PDF reader functionality
- "Internet speed" - Run speed test
- "Set an alarm" - Configure alarm

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Security Note

- Update the email and WhatsApp credentials securely
- Don't commit sensitive information
- Use environment variables for sensitive data

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Iron Man movies for inspiration
- Python community for the amazing libraries
- Contributors and testers

## Contact

For questions and support, please open an issue in the GitHub repository.

---
Built with ❤️ using Python
