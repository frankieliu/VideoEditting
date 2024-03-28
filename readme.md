# Download a video
## Find m3u8

1. Use chrome C-S-j
2. Network
3. Filter on m3u8

## Copy the URL and paste it

1. Get the referer from the headings of the request
2. Find the possible resolutions:

   youtube-dl -F --referer <REFERER> <URL>

## Choose a resolution

1. youtube-dl -f 1240 --referer <REFERER> <URL>

# Tools
## Trim a video
avidemux
mpv and mpv_slicing : https://github.com/Kagami/mpv_slicing

## Reencode a video
handbrake

# Subs
1. Upload video to youtube
2. Download subs: https://downsub.com/

# Git
## gh
# Install gh

```sh
brew install gh
gh auth login # will take you to the browser but there are other options for non-interactive
gh repo create repoName --private --source=. --remote=origin
git remote -v # will show the local is connected
git push -u origin main # will push to that connection
```

## Creating a personal access token
https://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-opening-br


# Loom

1. Search for "video" or "audio"
2. Note the long string xxxx
3. Search for this string xxxx
4. Look for the www.loom.com/embed at top and blue
5. Copy URL in a new tab
6. Open the video in Loom
7. Download the video
8. Download the transcript
 
## Subs

1. Look for .vtt
2. Copy URL in new tab
3. Save the .vtt file

## Translating subs

1. https://translate-subtitles.com/

# Circle

1. Look for assets.circle.so
2. Use the Network view and zoom on the very long blue line

# YouTube Studio

1. Create - to upload videos
2. You can edit the videos by clicking the upload dialogue
3. Put to child
4. Make unlisted

## Add to playlist

## Sort the playlist in YouTube
