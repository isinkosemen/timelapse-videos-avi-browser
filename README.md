# Water Kefir Timelapse Processor

A lightweight, reproducible project to **capture, process, and visualize timelapse videos** — designed for **Water Kefir fermentation** research and demonstration.  

Currently, we use a **dummy AVI timelapse video** for testing, but this workflow is ready for real kefir fermentation footage.

Dummy file source: https://www.engr.colostate.edu/me/facil/dynamics/avis.htm

## Project Purpose

- Capture and visualize **Water Kefir fermentation over time**.  
- Automate **video conversion and compression** using FFmpeg.  
- Create a simple, repeatable workflow for timelapse experiments and educational visualization.

## Installation & Usage — Step by Step

### **Step 1 — Install Homebrew**

Homebrew is a macOS package manager that lets you easily install command-line tools.

Run this command in your terminal to install Homebrew first:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


### **Step 2 — Install ffmeg to convert avi to mp4** 

```bash
brew install ffmpeg
```

### **Step 3 — Convert individual avi files to mp4 under videos folder**  

```bash
ffmpeg -i timelapse1.avi -c:v libx264 -crf 23 timelapse1.mp4
```

### **Step 4 — Update index.html file to include all mp4 videos**  


