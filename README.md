
# Merged Video Example
This example demonstrates how to create a webpage using Video.js to play two videos back-to-back automatically, creating a merged video experience similar to a YouTube ad.


## Prerequisites

    Web browser with HTML5 video support.
    Internet connection to load external libraries


## Usage

1. Video Playback:

    The webpage contains a Video.js player with two video sources (background-video.mp4 and file_example_MP4_480_1_5MG.mp4).

    The videos play back-to-back automatically. Once the first video (background-video.mp4) completes, the second video (file_example_MP4_480_1_5MG.mp4) starts, and vice versa.

2. Customization:

    You can replace the video sources in the <source> tags with your own video file URLs.

3. Styling:

    The webpage uses Bootstrap for styling. You can customize the styling by modifying the CSS in the <style> section.

4. Run Locally:

    The webpage can be opened locally using a web browser without the need for a web server.
## Troubleshooting

    If the second video is not playing after the first video, ensure that the video file URLs are correct and accessible.

    Verify that the web browser being used supports HTML5 video.
## Dependencies

    Bootstrap

    Video.js