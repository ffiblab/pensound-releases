### Improvements
- Simplified internal sample rate handling; pitch and grain synthesis now use a fixed correction constant, eliminating a class of edge-case audio artifacts
- Wider tonal variation with speed and pressure — faster strokes sound brighter, slower strokes darker (all tools)
- Improved amplitude modulation (AM) at low pressure for more lively sound even with a light touch
- Bidirectional pitch modulation based on pressure — a lighter grip raises the pitch slightly, while heavier pressure lowers it

### Bug Fixes
- Fixed audio distortion and electronic noise when switching output devices while virtual audio software (e.g., OBS) is running
- Fixed an issue where launching virtual audio software could immediately cause audio corruption
- Fixed a rare issue where audio engine could enter an unrecoverable state due to repeated unnecessary restarts triggered by spurious system notifications
