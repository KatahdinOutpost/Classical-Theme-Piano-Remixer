# Classical-Theme-Piano-Remixer
HTML based Piano remixer
<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/ac7838e3-5822-4cf9-8c9c-9ce0c32417b2" />
https://katahdinoutpost.github.io/Classical-Theme-Piano-Remixer/

🎹 Overview
Classical Piano Remixer is a fully standalone, browser-based music composition and arrangement tool built with vanilla HTML, CSS, and JavaScript. No installations, no dependencies, no server required — just open the file and perform.

Inspired by the great composers, it lets you compose, import, arrange, and export piano melodies with classical style presets, expressive dynamics, and a realistic piano synthesis engine — all powered by the Web Audio API.

✨ Features
Piano Synthesis Engine — Realistic piano tone using inharmonic partials, 3-string detuning, and hammer attack noise
Classical Style Presets — Six curated arrangements: Baroque, Romantic, Nocturne, Sonata, Waltz, and Étude
Note Entry — Type notes directly (e.g. C4 E4 G4 B4), tap the on-screen piano keys, or import a text score
Audio Melody Detection — Import .mp3, .wav, or .m4a files and auto-transcribe a melody using pitch detection
Articulation Control — Slide between Staccato, Portato, and Legato to shape note length and feel
Expressive Layers — Toggle bass octave, inner harmony, metronome pulse, hall reverb, and humanized timing
WAV Export — Render and download your full arrangement as a .wav file directly in the browser
Project Save & Load — Persist your score and settings to browser localStorage
Score Editor — Visual note chip editor to review and delete individual notes
Share Text — Copy a plain-text summary of your melody and settings to your clipboard
🚀 Getting Started
Download or copy the single .html file
Open it in any modern browser (Chrome, Edge, Firefox, or Safari)
Enter notes in the score field or tap the piano keys
Choose a style preset — Baroque through Étude
Click ▶ Perform with Piano to hear your arrangement
Export WAV to save your performance as an audio file
No build step. No npm. No internet connection required after the font loads.

🎼 How to Enter Notes
Notes follow the format [Note][Accidental][Octave]:

Format

Example

Meaning

Natural note

C4

Middle C

Sharp

F#4

F sharp, octave 4

Flat

Bb3

B flat, octave 3

Sequence

C4 E4 G4 B4

Space-separated melody

Supported range: C2 through A7 Supported accidentals: # (sharp) and b / B (flat)

🎭 Style Presets
Preset

Tempo

Character

🕯 Baroque

108 BPM

Crisp, articulate, ornate

🌹 Romantic

80 BPM

Expressive, full, flowing

🌙 Nocturne

58 BPM

Slow, atmospheric, with hall reverb

📜 Sonata

132 BPM

Bright, structured, dramatic

💃 Waltz

116 BPM

Lilting, rhythmic, graceful

Rows per page:

5
1–5 of 6

📁 File Import
File Type

How It's Used

.txt / .csv

Parsed as space or line-separated note names

.mp3 / .wav / .m4a

Pitch-detected and auto-transcribed to notes

Tip: Audio detection works best with solo piano, solo voice, or single-instrument recordings. Dense mixed tracks may produce rough results. Use the Detection Sensitivity slider to tune how many notes are captured.

🎛️ Controls Reference
Control

Description

Tempo

Speed in BPM — range 40 to 200

Articulation

Note length from Staccato (short) to Legato (long)

Brilliance

High-frequency brightness of the piano tone

Resonance

Strength of overtones and harmonic layers

Rubato / Timing

Adds natural timing push-pull between beats

Rows per page:

5
1–5 of 6

💾 Saving & Sharing
Save Score — Stores your notes and all settings in browser localStorage
Load Score — Restores the last saved score and settings
Copy Share Text — Copies a plain-text melody summary to your clipboard for easy sharing
🛠️ Technical Notes
Built with vanilla HTML5, CSS3, and JavaScript — zero dependencies
Audio engine uses the Web Audio API (AudioContext, OfflineAudioContext)
Piano synthesis models inharmonic string partials, three-string detuning, and a soft hammer noise burst
WAV export uses a custom PCM encoder — no external libraries needed
Pitch detection uses an autocorrelation algorithm on decoded audio frames
Fonts load from Google Fonts (Playfair Display, Lato) — app works offline but uses fallback fonts without a connection
⚖️ Rights & Usage
Use melodies you composed, own, or have licensed. Audio import is intended for:

Your own personal recordings and compositions
Public domain works you are arranging yourself
Content you have explicit permission to remix
🌐 Browser Compatibility
Browser

Status

Chrome / Edge 90+

✅ Full support

Firefox 90+

✅ Full support

Safari 14.1+

✅ Full support

Mobile Chrome / Safari

✅ Supported

Internet Explorer

❌ Not supported

Classical Piano Remixer — Compose with elegance. Perform with expression. Export with ease.
