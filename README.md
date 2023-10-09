# PCCFM

This repository contains MATLAB code that performs the retrieval of corresponding wavelengths for pixels in an image based on a mapping relationship between hue and wavelength.

## Usage

1. Ensure that you have MATLAB installed on your computer.

2. Download or clone this repository to your local machine.

3. Open MATLAB and navigate to the directory where you saved the code.

4. Make sure that the file "Hue_Wavelength_Mapping.mat" is available in the same directory. This file contains the pre-defined mapping relationship between hue and wavelength.

5. Run the MATLAB script "PCCFM_code.mlx".

6. A GUI dialog will appear, allowing you to select a TIFF image file image in PCCFM mode. Choose the desired file and click "Open".

7. The code will then iteratively retrieve the corresponding wavelength for each pixel in the image based on the hue value.

8. The resulting wavelength image will be displayed in a new figure.

## Prerequisites

- MATLAB: The code is written in MATLAB and requires MATLAB software to be installed on your system. The code has been tested with MATLAB version '9.9.0.1467703 (R2020b)'.

- Operating System: The code is platform-independent and can be run on Windows, macOS, and Linux operating systems. It has been tested on Microsoft Windows [Version 10.0.22621.1702].

## Files
- `code/`: This directory contains the MATLAB code files.
  - `PCCFM_code.mlx`: The main MATLAB script that performs the retrieval of wavelengths for pixels in an image.
  - `Hue_Wavelength_Mapping.mat`: A MATLAB MAT file that contains the mapping relationship between hue and wavelength.
- `dat/`: This directory contains example data files.
  
## Expected Run Time

The expected run time for the demo on a "normal" desktop computer can vary, but it is typically within a few seconds to a few minutes depending on the size of the input image and the processing power of your computer. In most cases, the computation is fast and should complete within seconds.

## License

GNU General Public License v3.0
