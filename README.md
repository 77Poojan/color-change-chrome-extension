# Color Changer Chrome Extension

A simple Chrome extension that changes the background color of the current webpage.

## Features
- Change webpage background color with one click
- Simple popup interface
- Built using Chrome Extension Manifest V3

## Project Structure

color-changer-extension  
├── manifest.json  
├── popup.html  
├── popup.js  


## Run Locally

1. Download or clone this project.

2. Open Google Chrome and go to:

chrome://extensions/

3. Enable **Developer Mode** (top right corner).

4. Click **Load unpacked**.

5. Select the extension folder.

6. The extension will appear in your Chrome toolbar.

## How to Use

1. Open any website (example: https://google.com).
2. Click the extension icon.
3. Click **Change Page Color**.
4. The page background color will change.

## Important Note

Chrome extensions **cannot run on internal Chrome pages** such as:

chrome://extensions  
chrome://settings  
chrome://history  

This is a Chrome security restriction.

## License
MIT
