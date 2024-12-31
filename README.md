## Spotify Playlist Downloader 🎵

This is a Py-based command-line program that allows you to download songs from a public Spotify playlist in **.mp3 format**. It combines the power of Spotify's API, YouTube search, and FFmpeg to fetch songs and save them locally in a folder named after the playlist.

### Demo
[Youtube](https://youtu.be/yW-w_28A82A?si=x5AEpkHEbHjA05er)

---

### This Program Does

   - You provide a Spotify playlist URL.
   - The program fetches the song names, artists, and Spotify links.
   - A CSV file is generated with song details (name, artist, Spotify link).
   - Each song is searched on YouTube, and the best match is downloaded in **MP3 format**.
   - The songs are saved in a folder named after the Spotify playlist.
   - Songs and their metadata are neatly organized in a folder.

---

### Setup Instructions

- Clone the Repository
- Install Dependencies
- Install the required Python libraries
- Set Up Spotify API Credentials
  - Visit [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
  - Create an app to get your **Client ID** and **Client Secret**.
  - Replace `your_client_id` and `your_client_secret` in the code with your credentials.
- Install FFmpeg
- FFmpeg is required to convert audio into MP3 format
  - Download from [FFmpeg website](https://ffmpeg.org/download.html) and add the `bin` folder to your system's PATH.
  - 
---

## How to Run the Program

- Open a terminal and navigate to the project folder.
-  Run the script:
   ```bash
   python main.py
   ```
3. Enter the **Spotify Playlist URL** when prompted.

---



## Folder Structure

After running the program, your project will look like this:
```
spotify-downloader/
│
├── My Playlist/           # Folder containing downloaded MP3s
│   ├── song1.mp3
│   ├── song2.mp3
│   └── ...
├── main.py                # The program file
├── My Playlist.csv        # CSV with song details
└── README.md              # You're here! :')
```

---

## Want to Contribute?

- **Frontend developers**: Build a simple GUI (e.g., a web app) to replace the CLI.
- **Backend developers**: Enhance error handling, add support for private playlists, or build a web API for this.
- **Anyone else**: Suggest features, optimize code, or improve documentation!

---
