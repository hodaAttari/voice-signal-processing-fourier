# Voice Signal Processing — Fourier & Filtering  

This project demonstrates fundamental **Digital Signal Processing (DSP)** techniques for audio signals using Python, NumPy, and SciPy.  
The code performs reading, transforming, filtering, speed manipulation, reversal, and mixing of `.wav` files — all from scratch with detailed visual plots.


## Operations Implemented  

It performs step‑by‑step:
- Reading and FFT (Fast Fourier Transform) of WAV files  
- Spectrogram visualization and amplitude‑frequency analysis  
- Low‑pass filtering of noisy signals using custom cut‑off ranges  
- Speed modification (slow / fast playback)  
- Voice reversal for time domain inversion  
- Mixing multiple signals with resampling to a common rate  


## Files  

`project-voice.ipynb` — Main notebook with all visualizations and plots  
`cleanpotc.wav` — Cleaned signal after Fourier low‑pass filtering  
`fastpotc.wav` — Example of speed‑up version (×2 playback)  
Additional files generated: `slowpotc.wav`, `revpotc.wav`, `mixpotc.wav`


## Run  

Install required packages:
```bash
pip install numpy scipy matplotlib
```

Run the notebook:
```bash
jupyter notebook project-voice.ipynb
```
Output Examples
During execution, the notebook produces plots such as:

Amplitude–Frequency curve before and after filtering
Spectrogram (time–frequency intensity map)
Reconstructed clean audio using inverse FFT
Audio output with different playback rates
Mixed signal plot showing combined frequency spectrum


🎯 Educational Goal
This mini‑project helps students understand how digital audio processing works —

how frequency‑domain manipulation (Fourier & filters) relates to time‑domain signal changes.

It bridges theory (FFT & filtering) to real‑world practice (cleaning, speed change, mixing).
