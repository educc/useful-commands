# useful-commands
Useful commands for linux/macos with minimum dependencies

# [whispercpp](whispercpp)
Bash script to transcript any video or audio file using whisper.cpp. 
 
## Requirements
- ffmpeg `brew install ffmpeg`
- whisper.cpp: see the installation details at https://github.com/ggerganov/whisper.cpp

# [videosummary](videosummary)
A python script to make summaries of youtube videos. 

## Requirements
- Python 3.11+
- yt-dlp: see the installation details at https://github.com/yt-dlp/yt-dlp
- whisper.cpp: download de `medium.en` model. See the installation details at https://github.com/ggerganov/whisper.cpp

## How to run
`python videosummary https://www.youtube.com/shorts/ddUIbUBAzD8`