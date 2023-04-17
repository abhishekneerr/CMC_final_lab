
This project was desined as a final submission for the course "Computational Music Creativity" taught by Sergi Jordà, Daniel Gómez-Marín and Behzad Haki.

## Consciousness 

We aimed to develop a real time reactive audio visual model, using Pure data and Ableton Live. The audio is produced in Ableton Live, Visuals and data processing is done in Pure data. The communication between both the software is done using OSC and MIDI messages. The current version is a standalone version where in once the song is played the visuals are generated automatically according to the audio events happening in ableton live. It can be modularized in order to perform live, to create visuals and audio in real time. 
For detailed explanation, check "report.pdf".

Github link to the project: https://github.com/abhishekneerr/CMC_final_lab
Video: https://youtu.be/l0DSrargaQY

main pd patch: main.pd

Requirements:
Softwares:
1. Ableton Live
2. Pure data

Plugins:
1. Serum
2. Valhalla Vintage Verb
3. Valhalla SuperMassive

Max for live devices:
1. OSC connection kit: https://www.ableton.com/en/packs/connection-kit/
2. Live grabber: https://www.showsync.com/tools

Pure data libraries:
1. OSC
2. IEMnet
3. Ofelia


Install/download all the requirements, setup midi bus for your OS, and run both ableton and pd at the same time. Press the play button in Pure data to play the song, and create window button to see the visual window.

