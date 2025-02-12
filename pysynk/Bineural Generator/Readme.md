# Bineural Generator

## Overview

Bineural Generator is a Python-based application that allows users to create and manipulate binaural beats using different waveforms. The application provides an intuitive GUI built with Tkinter and supports various frequency adjustments for custom audio generation.

## Features

- Generate binaural beats using **Sine, Square, Triangle, and White Noise** waveforms
- Adjustable frequency and volume settings
- Save generated audio files
- Real-time audio playback using **pygame**
- Simple and user-friendly graphical interface

## Requirements

Ensure you have the following dependencies installed before running the application:

```bash
pip install pydub pygame
```

Additionally, you need **ffmpeg** installed to handle audio processing. You can install it using:

- **Windows**: Download from [FFmpeg official website](https://ffmpeg.org/download.html)
- **Linux/macOS**: Install via package manager, e.g.,
  ```bash
  sudo apt install ffmpeg  # Debian-based
  brew install ffmpeg  # macOS
  ```

## Usage

1. Run the application:
   ```bash
   python bineural_generator.py
   ```
2. Choose a waveform and adjust the frequency.
3. Click **Play** to listen in real-time.
4. Click **Save** to export the generated audio file.

## Contributing

Feel free to fork this repository, submit pull requests, or report issues.

## License

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to the **pydub** and **pygame** communities for providing powerful audio manipulation tools.

