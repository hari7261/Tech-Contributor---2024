**# SnapTub - YouTube Video & Audio Downloader

**SnapTub** is a simple command-line tool for downloading videos and extracting audio from YouTube and other online streaming platforms using the `youtube_dl` library. The script provides an easy-to-use interface to download either video or audio, including entire playlists, in various formats.

## Features

- **Video Download**: Download YouTube videos in their default format.
- **Audio Download**: Extract audio from YouTube videos and convert it to MP3 format.
- **Playlist Audio Download**: Download and convert entire YouTube playlists to MP3 files.

## Requirements

- **Python** (compatible with Python 2.x and 3.x, though best with 2.x)
- **youtube_dl** library
- **FFmpeg** (required for audio extraction and conversion)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/hari7261/Tech-Contributor---2024/PyTube-master.git
cd Pytube-master
```

### 2. Install `youtube_dl` and `FFmpeg`

You will need to install `youtube_dl` and `FFmpeg` for this script to work.

```bash
# Install youtube_dl
pip install youtube_dl

# Install FFmpeg (Linux)
sudo apt-get install ffmpeg

# Install FFmpeg (macOS)
brew install ffmpeg
```

## Usage

Run the script using Python. The menu will guide you through the process.

```bash
python Pytube-master.py
```

### Main Menu

```
8888888b.       88888888888       888               
888   Y88b          888           888               
888    888          888           888               
888   d88P 888  888 888  888  888 88888b.   .d88b.  
8888888P"  888  888 888  888  888 888 "88b d8P  Y8b 
888        888  888 888  888  888 888  888 88888888 
888        Y88b 888 888  Y88b 888 888 d88P Y8b.     
888         "Y88888 888   "Y88888 88888P"   "Y8888  

{1}--Video Download
{2}--Audio Download
{3}--Audio PlayList Download
{99}--Exit
```

### Download Video

1. Select option `1` from the menu to download a video.
2. Enter the YouTube URL for the video.

```bash
PUT URL EX: https://www.youtube.com/watch?v=VIDEO_ID
```

The video will be downloaded in the best available format.

### Download Audio

1. Select option `2` from the menu to extract and download the audio from a video.
2. Enter the YouTube URL for the video.

```bash
PUT URL EX: https://www.youtube.com/watch?v=VIDEO_ID
```

The audio will be extracted and saved in MP3 format with 192 kbps quality.

### Download Playlist Audio

1. Select option `3` from the menu to download the audio for an entire YouTube playlist.
2. Enter the playlist URL.

```bash
EX: https://www.youtube.com/watch?v=lp-EO5I60KA&list=PLAYLIST_ID
```

The script will download all videos in the playlist and convert them to MP3 format.

### Quit

- Press `99` or type `n` when prompted to exit the program.

## Error Handling

If you encounter issues or need to interrupt the process, press `Ctrl+C` to safely stop the program.

## Notes

- The script is currently optimized for Unix-like systems (Linux/macOS). If using Windows, replace `clear` with `cls` in the script to clear the screen properly.
- The script uses `raw_input()` for reading input, which works with Python 2.x. For Python 3.x, replace it with `input()` for full compatibility.

## Contributing

Feel free to submit issues or contribute to the development by submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Coded by Hariom**  
