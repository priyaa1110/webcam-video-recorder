# Webcam Video Recorder

A browser-based webcam video recorder with playback and download capabilities.

## Features

- Live webcam preview with audio
- Record video with audio from webcam
- Recording timer with visual indicator
- Save multiple recordings in browser session
- Playback recordings in modal viewer
- Download recordings as WebM files
- Delete unwanted recordings
- Fully responsive design

## Usage

Open webcamvideorecorder.html in a modern web browser. Camera permissions required.

### How to Use

1. Click "Start Camera" to access webcam
2. Grant camera and microphone permissions when prompted
3. Click "Start Recording" to begin recording
4. Click "Stop Recording" to end recording
5. Recordings appear in the list below
6. Use Play, Download, or Delete buttons for each recording

### Controls

- Start/Stop Camera: Toggle webcam access
- Start Recording: Begin capturing video
- Stop Recording: End current recording
- Play: View recording in fullscreen modal
- Download: Save recording as .webm file
- Delete: Remove recording from list

## Technical Details

- Single HTML file with embedded CSS and JavaScript
- Uses MediaRecorder API for video capture
- getUserMedia API for webcam/microphone access
- WebM format with VP9/VP8 codec support
- Recordings stored in memory (lost on page refresh)
- Zinc theme with minimal design aesthetic

## Browser Compatibility

Requires modern browser with MediaRecorder API support:
- Chrome 49+
- Firefox 29+
- Safari 14.1+
- Edge 79+

## Privacy

All recording happens locally in the browser. No data is uploaded to any server.
Recordings are stored in browser memory and cleared when the page is closed.

## Notes

- Webcam and microphone permissions required
- Recordings are lost when page is refreshed
- File size depends on recording duration and quality
- Click outside modal to close playback viewer
