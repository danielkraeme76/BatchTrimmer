# BatchTrimmer

BatchTrimmer is a freeware desktop application for Windows that allows batch processing of audio files.  
It is designed to streamline repetitive editing tasks and provide a simple, efficient workflow.

Remove the stills at the beginning and end of your recordings. You can fix the clicks that occur at the cut points with fade-in and fade-out, and you can normalize the recordings in the same editing step.

LOFI vibes: Thanks to its wide range of target values for Bit-depth and Sample-Rate ​​down to 8 bit and 4 kHz, BatchTrimmer is also very well suited to quickly converting many files into a characteristic, retro-like sound.

## ✨ Features

- ✂️ **Silence trimming** at the beginning and end of files based on a configurable threshold (dBFS)
- 📈 **Normalization** using a peak-based method
- 🎚️ **Fade In / Fade Out** with adjustable duration (ms)
- 💾 **Export** to multiple formats: WAV, .AIFF
- ⚙️ **Output options**:
  - Bit depth: 8-Bit, 12-Bit, 16‑bit, 24‑bit, 32‑bit float
  - Sample rate: 4 kHz, 8 kHz, 11.25 kHz, 16 kHz, 22.50 kHz, 32 kHz 44.1 kHz, 48 kHz, 96 kHz
  - Custom output folder
  - Filename suffix
  - Overwrite option
- 📋 **Status log** showing progress and errors during batch processing

---

## 🚀 Installation & Usage

1. Download the latest release from the [Releases](./releases) section.  
2. Run `BatchTrimmer.exe`.  
3. Add your audio files, configure processing parameters, and click **Execute**.

---

## ⚖️ License

This software is provided as **Freeware**.  
- Free of charge for personal use  
- Redistribution, publication, or upload is **strictly prohibited**  
- No warranty, no liability  

See [LICENSE.txt](./LICENSE.txt) for full details.

---

## ℹ️ Notes

- Developed with Python 3.12, PySide6, and pydub.  
- ffmpeg is bundled and used internally.  
- Tested on Windows 10/11 (64‑bit).
