# ExperimentAudio
This repository contains the audio files used for PESQ experiments.

The Audio file `OneMinSpeech.wav` is the original audio file we used for the PESQ scoring.
While comparing the audio files in the PESQ metric, we first had to bring down the audio sample rate to 16kHz due to limitations of PESQ and stored the audio in a file `Tx.wav`. `Rx.wav` corresponds to audio received audio transmitted through the Tunnel diode. The PESQ score for the `Tx.wav` and `Rx.wav` pair is 2.484. 
