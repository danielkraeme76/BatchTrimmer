# BatchTrimmer

BatchTrimmer is a freeware desktop application for Windows that allows batch processing of audio files.  
It is designed to streamline repetitive editing tasks and provide a simple, efficient workflow.

## ✨ Features

- ✂️ **Silence trimming** at the beginning and end of files based on a configurable threshold (dBFS)
- 📈 **Normalization** using a peak-based method (e.g., target -1 dBFS)
- 🎚️ **Fade In / Fade Out** with adjustable duration (ms)
- 💾 **Export** to multiple formats: WAV, MP3, FLAC, OGG, AAC
- ⚙️ **Output options**:
  - Bit depth: 16‑bit, 24‑bit, 32‑bit float
  - Sample rate: 44.1 kHz, 48 kHz, 96 kHz
  - Custom output folder
  - Filename suffix
  - Overwrite option
- 📋 **Status log** showing progress and errors during batch processing

---

## 🚀 Installation & Usage

1. Download the latest release from the [Releases](./releases) section.  
2. Extract the archive (if applicable).  
3. Run `BatchTrimmer.exe`.  
4. Add your audio files, configure processing parameters, and click **Execute**.

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
