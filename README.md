# Language Translation Tool 

An interactive tool to **translate text between multiple languages** using Google Translate, with the ability to **play translations as audio** using text-to-speech (TTS). Designed to run in **Google Colab**, making it easy to use directly in your browser without setup.


## Features

- Translate text between **100+ languages**
- Auto-detect the source language
- Copy translations to the clipboard 
- Play translations as audio (TTS) directly in Colab
- Clear input and output fields with one click

## Installation

All dependencies can be installed directly in Colab:

```python
!pip install googletrans==4.0.0-rc1 gtts ipywidgets
```
    
## Usage

1. Open the notebook in Google Colab.

2. Run the first cell to install dependencies and initialize the UI.

3. Type text into the Input box.

4. Select the source and target languages from the dropdown menus.

5. Click Translate to see the translation.

6. Optional actions:

     Play TTS: Listen to the translation directly in Colab.

     Copy: Copy the translation to clipboard.

     Clear: Reset input and output fields.

## Example


Input: "Bonjour tout le monde"

Source: Auto-detect

Target: English

Output: "Hello everyone"

## Notes

1. Works best in Google Colab.

2. Clipboard functionality may depend on browser support.

3. Audio playback uses Colab’s audio player.

## Acknowledgements

1. googletrans — for translation

2. gTTS — for text-to-speech

3. ipywidgets — for interactive UI
## Authors

- [@Kaniz-Subarna](https://www.github.com/Kaniz-Subarna)

