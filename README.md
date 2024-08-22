
---

# ScribeFlow: Transcription and Translation Web App

ScribeFlow is a web application that allows users to transcribe audio files and translate the transcriptions into various languages using advanced machine learning models. The project is built using React, Vite, and Web Workers for efficient processing.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Audio Transcription**: Transcribe audio files to text using Whisper models.
- **Text Translation**: Translate transcribed text into multiple languages using the NLLB-200 model.
- **Real-time Feedback**: Shows real-time progress and status updates during transcription and translation.
- **Clipboard & Download**: Easily copy the results to your clipboard or download them as a text file.

## Deployment

Check out the app here [https://scribeflow.vercel.app/](#).

## Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **Vite** (for local development)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/ezstefan/ScribeFlow.git
    cd scribeflow
    ```

2. **Install dependencies**:

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Start the development server**:

    ```bash
    npm run dev
    # or
    yarn dev
    ```

    The application will be available at `http://localhost:5173`.

### Usage

1. **Upload an Audio File**:
   - Navigate to the homepage and upload an audio file or start an audio stream.
   - The app will automatically begin transcribing the audio.

2. **View Transcription**:
   - Once transcription is complete, you can view the text on the `Transcription` tab.

3. **Translate Text**:
   - Switch to the `Translation` tab, select a target language, and click `Translate`.
   - The translated text will be displayed once the process is complete.

4. **Copy or Download**:
   - Use the provided buttons to copy the transcription or translation to your clipboard or download it as a `.txt` file.

### Folder Structure

```
├── public/                 # Static files
├── src/
│   ├── components/         # React components
│   ├── utils/              # Utility files and workers
│   ├── App.jsx             # Main application file
│   ├── main.jsx            # Entry point for React
│   └── styles/             # CSS and styling files
├── README.md               # Project documentation
├── package.json            # Project metadata and dependencies
└── vite.config.js          # Vite configuration
```

### Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss improvements.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

### Acknowledgements

- **OpenAI** for Whisper models
- **Xenova** for the NLLB-200 translation model
- **React** and **Vite** for providing the framework for the web application

---
