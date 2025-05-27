# Video Downloader

## Need to finalise readme file

## Acknowledgements

This project uses [yt-dlp](https://github.com/yt-dlp/yt-dlp), a powerful audio/video downloader library.

### Things to include in the readme

- [ ] Introduction
- [ ] User guide
  - [ ] Downlaod
  - [ ] Usage
- [ ] Feedback

## Development Plan

### Current State

Currently removing some hard coding in the GUI and widget definitions

### Roadmap

Goals:

- [x] Initial creation of the GUI and widgets
  - [x] URL entry
  - [x] Download button
  - [x] Verification button
  - [x] Directory entry
  - [x] Directory browse Button
  - [x] File name entry
  - [x] Quality dropdown
- [x] Verification button Functionality
  - [x] Get video info
    - [x] Warning upon no entry
    - [x] Error catching for non-video link
    - [x] Error catching for extraction issues
    - [x] Generic error catching
  - [x] Display video info to user
    - [x] create function to make readable formats for the dropdown
    - [x] sort the formats from best to worst quality
  - [x] Update the file name entry with the video title
  - [x] Display error to user upon failure
- [ ] Directory Selection Functionality
  - [ ] Enable browse button to open folder selection window
  - [ ] Set default path in entry to user/video directory
    - [ ] Ensure validity for Windows, Mac OS, and Linux users
- [ ] Download button
  - [ ] Final verification that inputs have not changed
    - [ ] URL
    - [ ] Title
    - [ ] Directory
    - [ ] Format/Quality
  - [ ] Format yt_dlp input
    - [ ] format = user selected format
    - [ ] outtmpl = user selected directory + file name
  - [ ] Begin downloading from the URL
  - [ ] Progress tracking
    - [ ] Progress bar
- [ ] Create standalone .exe file
  - [ ] Ensure no need to external dependencies
  - [ ] way forward tbd
  