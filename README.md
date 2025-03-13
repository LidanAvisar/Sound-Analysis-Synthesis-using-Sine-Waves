# Sound-Analysis-Synthesis-using-Sine-Waves
A project that explores sound analysis and reconstruction by breaking down an audio file into its frequency components and attempting to recreate it using sine waves.


## Overview
This project focuses on analyzing an audio file and reconstructing it using **sine waves**. The goal is to break down a given **WAV file** into its **frequency components** and synthesize a similar sound by combining sine waves.

The project is divided into three main parts:
- **Loading and analyzing a given audio file** to extract frequency information.
- **Generating sine waves** that match the detected frequencies.
- **Reconstructing the original sound** using a sum of sine waves.

## Dataset
The dataset consists of **WAV audio files**, which can be downloaded from the provided Google Drive link. Each file contains a unique sound sample that needs to be analyzed and synthesized.

## Project Structure
### Data Loading & Preprocessing
- Loads an audio file from the dataset.
- Converts the audio waveform into a numerical representation.
- Visualizes the waveform and its frequency spectrum.

### Frequency Analysis & Synthesis
- Extracts dominant frequency components.
- Generates sine waves corresponding to detected frequencies.
- Combines sine waves to approximate the original audio.

### Evaluation
- Compares the generated sound with the original.
- Visualizes spectrograms and waveforms for comparison.

## Installation & Requirements
To run this notebook, you need **Python 3** and the following dependencies:

```sh
pip install numpy scipy matplotlib librosa
```

## Usage
Clone the repository:

```sh
git clone https://github.com/LidanAvisar/Sound-Analysis-Synthesis-using-Sine-Waves
cd Sound-Analysis-Synthesis
```

Open the Jupyter Notebook:

```sh
jupyter notebook "Sound Analysis & Synthesis.ipynb"
```

Run all cells to analyze and reconstruct the sound.

## Results & Analysis
The notebook visualizes:
- **Waveforms and spectrograms** of the original and generated audio.
- **Frequency breakdown** of the original sound.
- **Comparison plots** to evaluate the quality of reconstruction.
