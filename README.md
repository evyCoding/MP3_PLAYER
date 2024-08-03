# MP3 Player Made by yhevu

Here's the updated description for your MP3 player project, incorporating the additional details:

---

## MP3 Player Project

### Overview

This project is an MP3 player designed to provide high-quality audio playback with a user-friendly interface. It leverages modern hardware and software to deliver a robust and enjoyable listening experience. The project is implemented using a custom PCB, a microcontroller, an audio decoder, and a sleek LCD display.

### Features

- **Audio Playback**: Supports playing WAV and MP3 files up to 60 kbps.
- **User-Friendly Interface**: An intuitive interface displayed on an LCD screen for easy navigation and control.
- **Compact and Portable**: Designed to be lightweight and portable, making it easy to carry and use anywhere.
- **Audio Control Buttons**: Dedicated buttons for Play Next, Play Previous, and Pause functions.
- **Versatile Audio Output**: Can be connected to earphones, headphones, and speakers via an audio jack port.

### Hardware Components

- **Microcontroller**: Raspberry Pi Pico
- **LCD Display**: HS96L03W2C03
- **Audio Decoder**: PCM5102APWR
- **Power Supply**: Powered by 3 AAA batteries (4.5V total).
- **Control Buttons**: For Play Next, Play Previous, and Pause functions.
- **Audio Jack Port**: For connecting earphones, headphones, or speakers.

### Software Components

- **Programming Language**: CircuitPython
- **Audio Library**: import audiomp3, import audiocore, import audiobusio
- **File System**: import sdcardio

### Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone link of the repository
   ```
2. **Install Dependencies**:
   Ensure you have all the required libraries installed in your development environment.
3. **Upload the Code**:
   Use your preferred IDE to upload the code to the microcontroller.
4. **Order Hardware**:
   Order your PCB.
5. **Load Audio Files**:
   Copy your WAV and MP3 files to the designated storage (e.g., SD card) and insert it into the MP3 player.
6. **Power Up**:
   Insert 3 AAA batteries to power the device and enjoy your music.

### Usage

- **Navigation**: Use the buttons to navigate through the menu options.
- **Play/Pause**: Select a song and press the play button to start playback. Press again to pause.
- **Next/Previous**: Use the Play Next and Play Previous buttons to switch between songs.
- **Volume Control**: Adjust the volume using the designated control.
- **Playlist Management**: Create and manage playlists using the menu options.

### Contributions

Contributions are welcome! If you have any ideas or improvements, feel free to open an issue or submit a pull request. Please adhere to the project's code of conduct.

### Acknowledgements

- Special thanks to the developers of the libraries and tools used in this project.
- Thanks Hack club community for giving me the opportunity to make this happend & help making it and mass produce it for The Trail, https://youtu.be/ufMUJ9D1fi8?si=M68xeyEowXEnl5sm
