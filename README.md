#  Speech Processing Lab 6

 Pitch and Formant Estimation using FFT and STFT

 Objective

* Extract pitch, harmonics, and formants using FFT
* Analyze speech using STFT and spectrograms
* Compare narrowband and wideband spectrograms
* Understand time-frequency representation

 Files

* `speechprocessinglab6.ipynb` → Implementation
* `speechprocessinglab6report.pdf` → Report

 Audio Input Required

The original audio file is not included due to privacy reasons.

 How to create input:

1. Record a short speech sample (2–5 seconds)
2. Convert to `.wav` format
3. Ensure:

   * Mono channel
   * Sampling rate = 16000 Hz

 Convert using FFmpeg:

ffmpeg -i input.m4a -ac 1 -ar 16000 speech.wav

Place the file as:
speech.wav (same folder as notebook)

 How to Run

Install dependencies:

pip install numpy matplotlib librosa scipy

 Run:

jupyter notebook speechprocessinglab6.ipynb


 Outputs

* Time domain speech signal
* FFT spectrum (pitch & harmonics)
* Pitch contour (F0)
* Harmonics & formants peaks
* Spectrogram (STFT)
* Narrowband spectrogram
* Wideband spectrogram

 Key Concepts

* FFT → Frequency analysis
* STFT → Time-frequency analysis
* Spectrogram → Visual representation
* Narrowband vs Wideband trade-off

 Author : K. Shiva Gnana Yeseswini
BL.EN.U4AIE23013
