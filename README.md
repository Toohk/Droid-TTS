
# Droid TTS

Transform text into droid-like "beeps".

## Description

This Python script converts any given text into a sequence of droid-like "beeps". Each word from the input text is represented by a unique "beep" based on its specific characteristics (e.g., its first and last letter, word length, etc.).

## Prerequisites

- Python 3.x
- NumPy
- SciPy

You can install the dependencies using:


pip install numpy scipy


## Usage

1. Clone the repository.
2. Install the dependencies
2. Run the script with Python:


python droid-tts.py 'Text for the tts' 'output_filename.wav'


This will generate a `output_filename.wav` file containing the droid sound based on your input text.

## Features

- Converts any text into droid-like sounds.
- Generates a unique "beep" for each word based on its characteristics.
- Adds pauses between words and longer pauses between sentences.
