# YouTube to Transcript (YT2Script)

A simple web application that allows you to convert YouTube videos to text transcripts. This tool uses YouTube's API and speech recognition to provide accurate transcriptions of video content.

## Features

- Convert YouTube videos to text transcripts
- Support for multiple languages
- Simple web interface
- Download transcripts in various formats

## Setup

1. Install Python 3.8 or higher
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your YouTube API credentials:
   - Go to [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project
   - Enable the YouTube Data API v3
   - Create credentials (API key)
   - Save your API key in a `.env` file (see `.env.example`)

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Copy a YouTube video URL
2. Paste it into the input field
3. Click "Generate Transcript"
4. Wait for the processing to complete
5. Download your transcript

## Environment Variables

Create a `.env` file with the following variables:
```
YOUTUBE_API_KEY=your_api_key_here
```

## License

MIT License 