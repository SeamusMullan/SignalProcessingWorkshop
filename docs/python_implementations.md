# Python Implementations

This module contains Python code for classic digital signal processing (DSP) algorithms and graphics utilities. It is designed for both educational and practical use, and can be run standalone or imported into other projects.

## Requirements

- Python 3.12+
- Dependencies: See `requirements.txt` or `pyproject.toml` for a full list (notably: numpy, scipy, matplotlib).

## Structure

- **dsp/**: Core DSP algorithms
  - `audio/`: Audio processing utilities
  - `filters/`: Digital filter implementations
  - `fourier/`: Fourier transform and spectral analysis
  - `lpc/`: Linear Predictive Coding (LPC)
  - `ola/`: Overlap-Add methods
  - `phase_vocoder/`: Phase vocoder algorithms
  - `windowing/`: Window functions
- **graphics/**: Visualization and rendering tools
  - `graphs/`: General graphing utilities
  - `oscilloscope/`: Oscilloscope-style waveform display
  - `renderer/`: Rendering backends
  - `waveform/`: Waveform visualization
- **main.py**: Entry point for running demos or tests

## Usage

### Install dependencies

```sh
uv pip install -r requirements.txt
```

### Run the main script

```sh
python main.py
```

### Explore modules

- DSP algorithms: `dsp/`
- Graphics: `graphics/`

## Example: Running LPC

```python
from dsp.lpc import lpc
# Use lpc functions here
```

## Notes

- All submodules are importable; see code for available functions.
- Contributions and improvements are welcome.
