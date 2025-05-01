
# Adaptive AI Framework for Real-Time Personalized Music Generation & Music Therapy

## Project Overview
This repository contains an end-to-end implementation of an adaptive AI framework that extends Meta’s MusicGen Small to generate emotionally personalized music in real time, with tight integration into therapeutic workflows. By combining dynamic feature conditioning, adaptive learning, and a live user feedback loop, the system delivers high-fidelity, mood-aligned compositions—aimed at stress reduction, cognitive stimulation, and overall well-being.

## Key Features
- **Dynamic Feature Conditioning**  
  Inject tempo, spectral, and harmonic controls at inference time to steer musical mood and style.
- **Adaptive Learning Modules**  
  Continuously refine model outputs based on live user feedback, ensuring each session becomes more personalized.
- **Real-Time Feedback Loop**  
  WebSocket-powered React frontend captures user mood ratings and preference tweaks for on-the-fly adjustments.
- **High Performance**  
  Sub-second end-to-end generation (≈680 ms on NVIDIA A100), with measured improvements over MusicGen Small in tempo matching, spectral alignment, harmonic coherence, and mood congruence.


