# youtube-comments-dl
Command-line program to download comments of a YouTube video using YouTube API key

# Usage

To use the program to download comments of a video:

    cd youtube-comments-dl
    python youtube_comments_dl.py -v [VIDEO_URL or VIDEO_ID] -k [YOUR_API_KEY]
    
You can save your YouTube API key in 'youtube_api_key.txt' and use the program without the argument -k:

    python youtube_comments_dl.py -v [VIDEO_URL or VIDEO_ID]
