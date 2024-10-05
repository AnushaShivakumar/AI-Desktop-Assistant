

# OpenAI + Python-Powered AI Desktop Assistant

### Project Overview

**OpenAI + Python-Powered AI Desktop Assistant** is a conversational AI assistant that automates tasks and interacts naturally with users. Built using Python and OpenAI’s GPT-4, the assistant leverages speech recognition and natural language processing to execute tasks based on voice commands, providing a human-like conversational experience.

### Key Features
- **Voice Interaction:** Users can communicate with the assistant via voice commands.
- **Task Automation:** The assistant can perform tasks like setting reminders, managing calendars, sending emails, and conducting web searches.
- **Natural Language Understanding:** Powered by GPT-4, the assistant understands natural language input and responds accordingly.
- **Productivity Enhancement:** The assistant helps users by automating repetitive tasks, reducing manual effort, and improving productivity.

### Technologies Used
1. **Python**: Core programming language for the development of the assistant.
2. **OpenAI GPT-4 API**: Provides natural language understanding and human-like responses.
3. **SpeechRecognition Library**: Enables the assistant to understand and process spoken language.
4. **Pyttsx3**: Python text-to-speech conversion library to provide verbal responses.
5. **Natural Language Processing (NLP)**: To process and understand the user's spoken commands.
6. **APScheduler**: For scheduling tasks like reminders and calendar management.
7. **Smtplib (Email API)**: For sending emails directly from the assistant.

### Tools & Libraries
- **Python**: Programming the core functionality.
- **OpenAI API**: Used for integrating GPT-4 for intelligent responses.
- **SpeechRecognition**: Handles voice command input and processing.
- **Pyttsx3**: Converts text responses to speech, creating a seamless interaction.
- **APScheduler**: Allows scheduling of tasks like reminders and alarms.
- **Smtplib**: Python’s built-in library to send emails via the assistant.

### What This Project Does
- **Task Automation**: Users can ask the assistant to perform everyday tasks such as:
  - Setting reminders or alarms
  - Sending emails
  - Managing calendars
  - Conducting web searches
- **Voice Interaction**: The assistant listens to voice commands, processes them, and responds verbally.
- **Natural Conversations**: It interacts in a human-like manner, enhancing user experience.
  
### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up OpenAI API key:
   - Sign up for an API key at [OpenAI](https://beta.openai.com/signup/).
   - Add your API key to the environment variables or a config file.

4. Run the assistant:
   ```bash
   python main.py
   ```

### Usage
- Start the assistant and interact with it via voice commands.
- Example commands:
  - “Set a reminder for my meeting at 2 PM.”
  - “Send an email to John with the subject 'Project Update'.”
  - “What’s the weather today?”

