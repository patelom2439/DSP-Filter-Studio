🎧 DSP Filter Studio v2

Interactive Web-Based Digital Signal Processing Lab for Audio Filtering

📌 Overview

DSP Filter Studio v2 is an advanced web-based audio processing application designed to visualize and experiment with fundamental Digital Signal Processing (DSP) concepts in real time.

This project allows users to:

Load audio files (MP3/WAV)
Apply different filter types
Adjust filter parameters dynamically
Visualize both time-domain and frequency-domain responses

It serves as an educational as well as practical DSP tool for students and engineers.

🚀 Features
🎚️ 1. Multiple Filter Types

Supports industry-standard filters:

Butterworth – Smooth, flat response
Chebyshev Type I – Ripple in passband
Chebyshev Type II – Ripple in stopband
Bessel – Linear phase response
🎛️ 2. Adjustable Filter Order
Custom order input (1 – 1000)
Higher order → sharper cutoff
Performance warning for large orders
🎯 3. Q Factor Control
Manual Q adjustment (0.1 – 20)
Presets included:
0.5 (overdamped)
0.707 (critical damping)
1.0, 2.0, 10.0 (resonant)
🎵 4. Real-Time Audio Processing
Uses Web Audio API
Parallel processing:
Original signal
LPF output
BPF output
HPF output
Live mixing and playback
🎚️ 5. Frequency Controls (Log Scale)
Range: 20 Hz – 20 kHz
Logarithmic sliders for accuracy
Includes:
Low Pass Cutoff
Band Pass Range (Low & High)
High Pass Cutoff
📊 6. Advanced Visualizations
📈 Frequency Response Graph
Log-scale frequency axis
Dynamic Nyquist frequency (Fs/2)
Shows:
LPF, BPF, HPF curves
-3 dB reference line
🌊 Time Domain Waveform
Real-time signal visualization
📉 Magnitude Spectrum (PSD)
Frequency energy distribution
🎼 Full Track Overview
Seek bar with waveform preview
🎛️ 7. Channel Gain Control

Control volume (in dB) for:

Original signal
LPF output
BPF output
HPF output
👁️ 8. Signal Visibility Toggle

Enable/disable:

Original
LPF
BPF
HPF
Mixed signal
🎮 9. Playback Controls
Play / Pause
Stop
Skip ±5 seconds
Seek via waveform
📂 10. File Handling
Drag & Drop support
Manual file selection
Demo audio included
🧠 Technical Details
🔧 Core Technologies
HTML5
CSS3 (Custom UI + Dark Theme)
JavaScript (Vanilla)
Web Audio API
⚙️ DSP Implementation

The system uses:

Biquad Filters for real-time processing
Mathematical models for:
Butterworth response
Chebyshev Type I & II
Bessel approximation
📐 Key DSP Concepts Used
Nyquist Frequency (Fs/2)
Logarithmic Frequency Scaling
Filter Order & Roll-off
Q Factor (Resonance)
Frequency Response Analysis
Power Spectral Density (PSD)

🎯 Applications
🎓 DSP Laboratory Experiments
🎧 Audio Signal Analysis
🔊 Sound Engineering Practice
🧪 Filter Design Understanding
📊 Visualization of DSP Concepts
📸 UI Highlights
Modern cyber-style UI
Dark theme optimized for long use
Real-time interaction
Clean and structured layout
⚠️ Limitations
High filter order may affect performance
Uses browser processing (depends on system capability)
Ideal mathematical model used for graph visualization
👨‍💻 Author

Om S. Patel
Electronics Engineering Department
Birla Vishvakarma Mahavidyalaya

📅 Academic Year

2024 – 2025
