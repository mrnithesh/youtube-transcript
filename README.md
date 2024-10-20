# YouTube Video Transcript Generator with AI Refinement

This is a Streamlit-based web application that allows users to extract transcripts from YouTube videos and refine them using Google's Gemini AI. The app fetches the transcript, corrects errors in grammar, spelling, and punctuation, and improves readability while maintaining the original meaning of the video content.

## Features

- Extracts transcript from YouTube videos using the [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api/).
- Uses [Google Gemini AI](https://developers.generativeai.google/) to refine the transcript for better readability and clarity.
- Provides both the original and refined transcripts for comparison.
- Simple, user-friendly interface built with [Streamlit](https://streamlit.io/).

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.x
- Streamlit
- YouTube Transcript API
- Google Generative AI SDK (for accessing Gemini AI)

You can install the dependencies via `pip`:

```bash
pip install streamlit youtube-transcript-api google-generativeai
```

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/youtube-transcript-generator.git
```

2. Navigate to the project directory:

```bash
cd youtube-transcript-generator
```

3. Create an environment variable for your Google API key or enter it directly in the app.

4. Run the Streamlit app:

```bash
streamlit run app.py
```

5. Open your browser to `http://localhost:8501` to interact with the app.

## Usage

- Input a valid YouTube video URL.
- Provide your Google API key for AI processing.
- The app will display the original and refined transcripts.

## API Key

To use the Gemini AI model, you need to generate an API key from Google Cloud:

1. Visit the [Google Cloud Console](https://console.cloud.google.com/).
2. Enable the Google Generative AI API.
3. Generate an API key and provide it to the app.

## Project Structure

```
├── youtube.py          # Main Streamlit app file
├── README.md           # This file
└── requirements.txt    # Required packages for the project
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any queries or further information, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/mrnithesh/) or email at mr.nithesh.k@gmail.com.
