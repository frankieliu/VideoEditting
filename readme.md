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
2. Download sub

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