Install Homebrew first:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install ffmpeg

ffmpeg -i timelapse1.avi -c:v libx264 -crf 23 timelapse1.mp4

https://www.engr.colostate.edu/me/facil/dynamics/avis.htm

