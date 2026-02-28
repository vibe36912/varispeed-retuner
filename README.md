# Varispeed Retuner

A web-based tool for adjusting the pitch and speed of audio files and aligning them to different tuning standards.

## Features
* **Import:** Drag and drop media files (WAV, MP3, MP4, WebM).
* **Visualize:** View frequency distribution mapped to a musical pitch class profile (PCP) graph. 
* **Adjust:** Modify audio pitch and playback speed using cents, speed percentages, or semitones.
* **Tune:** Overlay reference grids (ISO 440 Hz, Verdi 432 Hz, Pythagorean, Just Intonation) and manually or automatically snap audio peaks to specific alignments.
* **Export:** Save the modified audio as WAV or MP3, or render it as a video (MP4/WebM) with a static background image.

## Usage
No installation or backend is required. Simply open the `index.html` file in any modern web browser. 

## Dependencies
The tool runs entirely client-side and fetches the following libraries via CDN for media export:
* [lamejs](https://github.com/zhuker/lamejs) (MP3 encoding)
* [mp4-muxer](https://github.com/Vanilagy/mp4-muxer) (MP4 container rendering)
* [webm-muxer](https://github.com/Vanilagy/webm-muxer) (WebM container rendering)
