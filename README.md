# text-to-speech-cli

This Python command-line utility uses the `pyttsx3` library to convert text into speech. The script takes a list of names and reads them aloud in sequence, demonstrating the use of voice rate adjustment and basic text-to-speech functionality.

## Features

- **Text-to-Speech Conversion**: Convert any string of text into audible speech.
- **Adjustable Voice Rate**: Modify the speed of the speech for better clarity or effect.
- **Sequential Speaking**: Speak through a list of strings (names) one by one with a brief pause between each.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sjschhabra/text-to-speech-cli.git
   ```

2. Navigate to the project directory:

   ```bash
   cd text-to-speech-cli
   ```

3. Ensure you have Python 3.x installed on your system.

4. Install the `pyttsx3` library:

   ```bash
   pip install pyttsx3
   ```

## Usage

1. Run the script:

   ```bash
   python text_to_speech.py
   ```

2. The script will read the names in the predefined list sequentially.

### Example Output

When running the script, the output will be as follows (in audible speech):

- "Hello"
- "World"

## Code Overview

Here’s a brief explanation of the code:

- **Voice Rate and Selection**: The `set_voice_rate` function sets the desired voice and speed for speech.
- **Speak Functionality**: The `speak` function initializes the speech engine and calls the `say` method to convert text to speech.
- **Sequential Speaking**: The script iterates over the list of names, speaking each name with a 0.5-second pause in between.
