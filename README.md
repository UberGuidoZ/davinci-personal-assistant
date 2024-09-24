# Okay DaVinci
---------------------------------------------------------------------------------------------------------
This script is a voice-based personal assistant powered by OpenAI's ChatGPT. It listens for a trigger phrase ("Okay DaVinci"), transcribes the user's speech input, generates a response using ChatGPT, and converts the response into speech using the Elevenlabs text-to-speech module. The assistant engages in a conversation with the user, asking for satisfaction with the response and generating a new response if necessary. The script also includes logging functionality and API key handling.
---------------------------------------------------------------------------------------------------------

## Table of Contents

| Section     |
|-------------|
| [Program Information](#program-information)      |
| [Installation](#installation)                      |
| [Usage](#usage)                             |
| [Contributing](#contributing)                            |
| [License](#license)                   |

## Program Information

|             |                                |
|-------------|--------------------------------|
| **Author**  | CaliNux                        |
| **Date**    | 6/14/2023                      |
| **Language**| Python                         |
| **OS**      | Windows 11                     |
| **Version** | v.04                           |


---------------------------------------------------------------------------------------------------------
## Installation
---------------------------------------------------------------------------------------------------------

Download pip and python if you have not already:
https://pip.pypa.io/en/stable/installing/
https://www.python.org/


Open powershell in windows and run the following command:


pip3 install speechrecognition pyttsx3 openai elevenlabs pygame pyaudio



---------------------------------------------------------------------------------------------------------
## Usage
---------------------------------------------------------------------------------------------------------

To use Okay DaVinci, follow these steps:

1. Sign up for an API key from OpenAI (ChatGPT) and Elevenlabs.
2. Replace "CHATGPT API HERE" in the config.txt file located in the config folder with your actual ChatGPT API key.
3. Similarly, replace "ELEVENLABS API HERE" inside the config.txt file with your Elevenlabs API key.
4. After replacing the API keys, you can run Okay DaVinci to utilize the speech recognition and text-to-speech functionalities provided by the respective APIs.

API Key Registration Links:
- OpenAI: [https://openai.com/](https://openai.com/)
- Elevenlabs: [https://beta.elevenlabs.io/speech-synthesis](https://beta.elevenlabs.io/speech-synthesis)


-Once the script is running, it will be in a listening state, waiting for a trigger phrase. 
-The default trigger phrase is "Okay DaVinci." You can modify this phrase as per your preference.

-When you want to interact with the personal assistant, say the trigger phrase followed by your command or query. 
-For example, say "Okay DaVinci", patiently await DaVinci's response before posing your question, such as "What's the capital of Montana?"

-The personal assistant will respond to your input with a concise answer within 30 words, while maintaining proper language etiquette.

-After receiving the response, the personal assistant will ask if it's acceptable by saying phrases like "Is this satisfactory?" or "Is this sufficient?" You can respond with "yes" or "no."

-If you respond with "yes," the conversation ends. If you respond with "no," the personal assistant will retry generating a response based on your previous input.

-You can exit the conversation at any time by saying keywords like "nevermind," "exit," or "quit."


Note: Make sure you have a working microphone connected to your device for voice input, and ensure that your surroundings are relatively quiet for accurate speech recognition.


---------------------------------------------------------------------------------------------------------
## Contributing
---------------------------------------------------------------------------------------------------------

ReadMe updated by [UberGuidoZ](https://github.com/UberGuidoZ/)


---------------------------------------------------------------------------------------------------------
## License
---------------------------------------------------------------------------------------------------------

This script is strictly intended for individual personal use and is not authorized for commercial purposes.
