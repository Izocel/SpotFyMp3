# SpotfyMp3

## Set-up
1. Clone this repository
2. Install all the required libraries from requirements.txt into the Python path (must keep libraries up to date)
3. Download the ffmpeg and ffprobe executables from http://ffmpeg.org/download.html and place them in your Python path (must keep file versions up to date)
4. Setup your playlists data in settings.json

## Usage
1. Run the SpotifyDownloaderUI.py file with python3 (I wrote the program using Python 3.8.1)
2. select a playlist to update it or updateAll at first
3. The output folder for downloaded playlists will be created adjacent to the location of the Python file

# Tips

Click the three dots at the top of a playlist (on the desktop version of Spotify), click share, and click "Copy Spotify URI" to retrieve the playlist's URI.
Make sure your version of youtube_dl is up to date, as if it is not, the downloading commands will likely be unsuccessful. To update youtube_dl after it is already installed with pip, run: sudo pip install -U youtube-dl (or run: python3.10 -m pip install youtubedl)
