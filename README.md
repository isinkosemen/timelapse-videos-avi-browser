# Water Kefir Timelapse Processor

A lightweight, reproducible project to **capture, process, and visualize timelapse videos** — designed for **Water Kefir fermentation** research and demonstration.  
Currently, we use a **dummy AVI timelapse video** for testing, but this workflow is ready for real kefir fermentation footage.

## Project Purpose

- Capture and visualize **Water Kefir fermentation over time**.  
- Automate **video conversion and compression** using FFmpeg.  
- Create a simple, repeatable workflow for timelapse experiments and educational visualization.

## ⚙️ Installation & Usage — Step by Step

### 🪄 **Step 1 — Install Homebrew**

Homebrew is a macOS package manager that lets you easily install command-line tools.

Run this command in your terminal to install Homebrew first:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" ```



Install Homebrew first:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install ffmpeg

ffmpeg -i timelapse1.avi -c:v libx264 -crf 23 timelapse1.mp4

https://www.engr.colostate.edu/me/facil/dynamics/avis.htm

