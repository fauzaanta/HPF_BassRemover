# HPF_BassRemover
## Background
The Audio Filter: Bass Remover application was developed to address the need for a tool capable of filtering out bass frequencies from audio files. Bass frequencies, characterized by their strong energy, can sometimes disrupt audio balance, introduce distortion, or fail to meet listener preferences. By implementing a High-Pass Filter (HPF) using a Finite Impulse Response (FIR) filter, the program effectively reduces low-frequency components while preserving the integrity of higher frequencies.

## Objectives
The app aims to:
1. Remove Bass Components: Eliminate bass frequencies below a user-defined cutoff frequency.
2. Enhance User Control: Provide adjustable settings for cutoff frequency, audio range, and windowing methods.
3. Implement Advanced Filtering: Support four windowing methods—Hamming, Hanning, Kaiser, and Blackman—for optimized frequency response and minimal spectral leakage.
4. User-Friendly Interface: Allow users to load .wav files, view before-and-after visualizations, and save filtered audio outputs.
5. Flexibility: Introduce two operational modes:
  - Audio Filter Mode: To apply the bass remover to an audio file.
  - Filter Mode: To display HPF characteristics without processing an audio file.

## Limitations
- File Format Dependency: The app supports only .wav audio files.
- Parameter Sequence Requirement: Users must input parameters (e.g., time range) in a specific order before selecting the windowing type.
- Limited Automation: The app does not automatically handle parameter configurations, requiring manual adjustments by the user.
- Narrow Scope: The focus is exclusively on bass removal and HPF visualization, without broader audio processing features.

---
This application demonstrates a practical implementation of digital signal processing principles, providing users with a robust tool for bass removal while highlighting areas for future enhancement.
