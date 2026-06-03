# YouTube Helper

A lightweight YouTube utility built with Python, Google Colab and the YouTube Data API.

Originally created as a personal tool for searching and organizing YouTube content in environments where the standard YouTube frontend may be unavailable or inconvenient.

## Features

- Search YouTube channels by name
- Search videos by keywords
- Find channels by ID
- Save and manage selected channels locally
- Retrieve video metadata and thumbnails
- Work with playlists and uploads
- Optional video downloading via yt-dlp
- Google Drive integration for persistence

## Tech Stack

- Python
- YouTube Data API v3
- Google Colab
- Google Drive
- yt-dlp

## Requirements

Install dependencies:
``` bash
pip install google-api-python-client yt-dlp requests
```

## API Key

Create a YouTube Data API key in Google Cloud Console.

In Google Colab:
``` python
python from google.colab import userdata 
API_KEY = userdata.get("YOUTUBE_API_KEY")
```

## Usage

Run the notebook or Python script and follow the interactive prompts.

The utility allows:
- searching for channels;
- browsing video metadata;
- saving selected creators;
- managing a lightweight local YouTube content database.

## Storage

Channel data is stored locally in:

``` text
channels.json
```

When using Google Colab, the file can be persisted through Google Drive mounting.

## Notes

This project was built primarily as a lightweight personal utility and API experiment rather than a production-ready application.

The focus was on:
- API interaction;
- lightweight automation;
- cloud-hosted workflows;
- personal tooling and infrastructure experimentation.

## License

MIT
