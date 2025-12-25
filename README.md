# Vocal-Remover-MATLAB
Strip lead-vocal from stereo pop songs in one click.  
No training, no AI—just classic signal-processing: L/R subtraction and two FIR band-stop filters.

# What it does
- Reads any stereo MP3
- Cancels centered vocal by (L – R)
- Removes leftover vocal energy with 150-600 Hz & 1.6-3.6 kHz FIR band-stop filters
- Writes new stereo WAV ready for karaoke practice

# Quick start
```matlab
>> vocal_remover('music1.mp3');
```
Output: `music1_no_vocal.wav` in the same folder.

# Requirements
- MATLAB + Signal Processing Toolbox
- No extra libraries

# License
MIT – feel free to fork and tweak filter bands.
