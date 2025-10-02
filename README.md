# Low_Pass_Filter_Analysis_Ananyashree
Using Wavegen, sine waves at 100 Hz–10 kHz were applied to the RC filter. Scope measured input/output amplitudes. Gain in dB was calculated as 20·log10(Vout/Vin). Results were plotted as Gain vs Frequency on a logarithmic axis to show filter response.

# Low-Pass Filter Assignment
Analog Systems Lab  

## Assignment Objectives
- Analyze the frequency response of a fixed RC Low-Pass Filter.  
- Use WaveForms tools (Wavegen & Scope) for experimental measurements.  
- Automate part of the experiment using Python scripts (WaveForms SDK).  
- Document results and observations using Git and GitHub.  

## Steps Taken
### Part 1: Frequency Response Analysis (WaveForms GUI)
- Generated sine waves at different frequencies (100 Hz, 500 Hz, 1 kHz, 2 kHz, 5 kHz, 10 kHz).
- Measured output using Scope tool.
- Recorded attenuation trend with frequency.

### Part 2: WaveForms SDK Automation
- Wrote a Python script using WaveForms SDK.
- Automated waveform generation and data capture.
- Saved measurement data as CSV in `data/`.

### Part 3: Git and GitHub Documentation
- Organized repository with folders: `data/`, `images/`, `scripts/`.
- Added code, plots, and observations.
- Used Git commits to track changes.

## Key Observations and Outcomes
- The RC low-pass filter attenuates higher frequencies as expected.
- At low frequencies, output ≈ input amplitude.
- At higher frequencies (above cutoff), output significantly drops.
- Verified theoretical vs experimental results (close agreement).
