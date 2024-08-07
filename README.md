<p align="center">
  <img src="https://user-images.githubusercontent.com/115654234/213008369-a3a3cc5b-498d-47ea-bd36-4569ce6c4e51.png">
</p>

## EDM-TR8 Dataset

EDM-TR8 is an open audio dataset composed of a series of drum recordings in the style of electronic dance music (EDM). This dataset primarily focuses on the iconic sounds of the Roland TR-808 drum machine with additional electro synth drums. The dataset contains 3,790 audio loops recorded in uncompressed stereo WAV format, generated with custom audio samples and a MIDI dataset used for training symbolic music models.

## Dataset

The primary objective of this dataset is to provide accessible content for machine learning applications in music and audio research. Some potential use cases for this dataset include tempo detection and classification, drum rhythm analysis, audio-to-MIDI conversion, source separation, automated mixing, music information retrieval, AI music generation, sound design and signal processing.

**Specifications**

- 3790 audio loops (approximately 9 hours)
- 24-bit WAV format
- BPM labeled
- Tempo range: 95–130bpm
- Variational drum patterns
- Multi-genre rhythm styles

## Examples

See examples folder to preview mp3 demos.


## License

This dataset is developed by WaivOps, a crowdsourced music project managed by sound label company Patchbanks. All recordings have been compiled by verified sources for copyright clearance.

The EDM-TR8 dataset is licensed under Creative Commons Attribution 4.0 International [(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
## Download

The audio files are provided in 24-bit WAV format and encoded at 44.1kHz.

Direct Download (4.4GB) [edm_tr9_drm_id_001.gz](https://zenodo.org/records/13257814/files/edm_tr8_drm_id_001-0013_wav.tar.gz?download=1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13257814.svg)](https://doi.org/10.5281/zenodo.13257814)
## File Name Reference

| **Label**             | **Reference**                                                  |
| ----------------- | ------------------------------------------------------------------ |
| bpm  | The tempo of the audio file|
| edm | Main genre (edm)|
| drm | instrument (drums)|
| id | Identification number|
| _00 | Playlist track number|

## Citation

If you use this dataset for a research or development project, please cite the following references:
```bash
@misc{EDM-TR8,
author = {WaivOps},
title = {WaivOps EDM-TR8: Open Audio Resources for Machine Learning in Music},
year = {2024},
doi = {10.5281/zenodo.13257814},
url = {https://doi.org/10.5281/zenodo.13257814},
}
```
## Additional Info

For any questions or feedback please email info@patchbanks.com.
