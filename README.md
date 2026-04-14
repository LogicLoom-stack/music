# Experience Pro: Digital Remix Studio

**A Cloud-Synced Multi-Layer Digital Audio Workstation**

`Experience Pro` is a high-fidelity digital audio workstation built for real-time performance and collaborative remixing. It combines a sophisticated **Tone.js** synthesis engine with **Firebase** cloud persistence, allowing users to build, save, and export complex orchestral and electronic compositions.

### Orchestral Architecture
The studio is divided into three primary instrumental sections, all controlled via a precision-mapped keyboard interface:
*   **Concert Grand Piano:** High-fidelity Salamander Grand Piano samples.
*   **Orchestral Bass:** A low-frequency triangle-oscillator synth for harmonic foundations.
*   **Remix Percussion:** A 6-part synthesized drum machine (Membrane, Noise, and Metal synths).

### Studio Features
*   **6-Layer Multitrack Recording:** Record up to 6 independent loops with per-layer volume, speed (0.5x to 3x), and beat-length controls.
*   **Cloud Persistence:** Full integration with **Firestore** to save and restore session states (volumes, speeds, and recorded sequences) across devices.
*   **Master Mastering Chain:** All audio is processed through a low-pass filter, feedback delay, 7-second lush reverb, and a master compressor.
*   **Master Export:** Real-time `.webm` recording of the master output for instant download of performances.

### Technical Stack
*   **Frontend:** React, Tailwind CSS
*   **Audio Engine:** Tone.js (Web Audio API)
*   **Backend:** Firebase (Auth & Firestore)
*   **Deployment:** Optimized for Vercel/Netlify environments.

---
*Created by Charu Kalia | Senior Program Manager & Fledgling Artist*
