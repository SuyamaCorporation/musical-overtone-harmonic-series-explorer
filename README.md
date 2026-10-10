# Musical Overtone & Harmonic Series Explorer

Interactive harmonic series visualiser and player using the Web Audio API with real-time frequency and music theory analysis.

## Key Features

- Enter any fundamental frequency (20–2000 Hz); table updates instantly showing all 16 harmonics with Hz, note name, cents deviation from equal temperament, and interval name
- Play All (simultaneous), Play Each (sequential at 0.3 s intervals), and Play Octave Chord (harmonics 1/2/4) modes
- Per-harmonic toggle switches enable or disable individual partials from playback and the spectrum chart
- Canvas amplitude spectrum bar chart with gradient fill, coloured by harmonic number
- Graceful degradation when Web Audio API is unavailable; table and chart remain fully functional
